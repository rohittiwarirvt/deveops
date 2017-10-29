FROM nginx

LABEL maintainer "Rohit Tiwari <rohittiwarirvt@gmail.com>"

EXPOSE 80

RUN  apt-get update && \
     apt-get install -y mysql-client curl

RUN apt-get update && apt-get install -y vim

RUN mkdir -p /var/www/public
RUN chown -Rf www-data:www-data /var/www/public


