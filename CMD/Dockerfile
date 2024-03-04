FROM almalinux:8
RUN yum install nginx -y 
RUN echo "This is dockerfile for creating the custom docker images" > /usr/share/nginx/html/hello.html
#This daemon off cmd makes our container running
CMD [ "nginx", "-g", "daemon off" ]

