FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/
ENTRYPOINT [ "nginx","-g","daemon off;" ]