FROM php:8.2-apache


RUN docker-php-ext-install mysqli pdo_mysql


RUN a2enmod rewrite


COPY php.ini /usr/local/etc/php/conf.d/php.ini