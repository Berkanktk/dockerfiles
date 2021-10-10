FROM php:8.0-apache
WORKDIR /var/www/html

RUN docker-php-ext-install mysqli

COPY index.php index.php
COPY src/ src
EXPOSE 80
