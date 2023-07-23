FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
#command  to run nignx container in forground
RUN echo "wellcome nginx" > /usr/share/nginx/html/hello.html
CMD [ "nginx","-g","daemon off;"]
#CMD [ "sleep","20" ]