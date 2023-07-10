FROM tomcat:8-alpine
LABEL maintainer="koppada.parasuk@gmail.com"
ADD warfiles /usr/local/tomcat/webapps/
EXPOSE 8080
CMD [“catalina.sh”, “run”]