FROM php:7-fpm
MAINTAINER kaotil

RUN apt-get update && apt-get install -y \
    git \
    vim \
 && apt-get clean 

RUN git clone https://github.com/kaotil/kaotil.com.git /var/www/kaotil.com
