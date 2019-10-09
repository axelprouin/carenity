FROM php:7.3-fpm

WORKDIR /var/www/html

RUN apt update
RUN apt install
RUN docker-php-ext-install pdo pdo_mysql mysqli

CMD ["php-fpm"]
