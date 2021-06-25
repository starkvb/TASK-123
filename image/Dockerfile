FROM ubuntu:latest

RUN apt update -y
RUN apt install nginx -y
RUN apt install php -y

COPY .index.php /usr/share/nginx/html/index.php

EXPOSE 80
