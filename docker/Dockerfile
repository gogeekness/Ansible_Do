# Version 0.0.1

FROM ubuntu:18.04
MAINTAINER mantainer_name "rdeseke@gmail.com"
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Default page.  Nginx is in your container. ' >/usr/share/nginx/html/index.html
EXPOSE 80
