FROM ubuntu:14.04

EXPOSE 9000

RUN apt-get update && apt-get install -y software-properties-common && \
    LANG=C.UTF-8

RUN add-apt-repository ppa:ondrej/php \
    && apt-get update


