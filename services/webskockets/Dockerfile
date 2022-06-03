FROM php:8.0-fpm

RUN apt-get update
RUN docker-php-ext-install pdo pdo_mysql mysqli pcntl


CMD [ "/bin/bash", "-c","php artisan websockets:serve" ]