# php5.6-fpm

FROM php:5.6-fpm
RUN docker-php-ext-install mysqli && docker-php-ext-install mysqli && docker-php-ext-install pdo_mysql
