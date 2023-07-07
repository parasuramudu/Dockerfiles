# base os
FROM almalinux:8
# instaling or updating required packages
RUN yum update -y
# here instaling web server
RUN yum install nginx -y 
# remome in the nginx server default index.html
RUN rm -rf /usr/share/nginx/thml/index.html
# here coping app code
COPY Green/ /usr/share/nginx/thml/
#here starting nginx server
CMD [ "nginx","-g","daemon off;"] 