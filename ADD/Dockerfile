FROM tomcat:8-alpine
LABEL maintainer="koppada.parasuk@gmail.com"
ADD warfiles/prodapp.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
#2
# FROM almalinux:8
# ADD  https://github.com/techworldwithsiva/docker-install-commands/blob/master/docker-install.sh /tmp/docker.sh
# ADD  sample-1.tar /tmp/