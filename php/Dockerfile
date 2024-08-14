FROM php:8.3-fpm

RUN apt update && \
    apt install -y zip libzip-dev libpng-dev libicu-dev libxml2-dev

RUN docker-php-ext-install mysqli pdo pdo_mysql gd zip intl xml

COPY php.ini /usr/local/etc/php/conf.d/php.ini

RUN apt clean