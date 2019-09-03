ARG M2_PHP_VERSION=""
FROM php:${M2_PHP_VERSION:+${M2_PHP_VERSION}-}fpm-alpine


RUN apk update; \
    apk upgrade;

#RUN docker-php-ext-install mysqli
#RUN docker-php-ext-install pdo pdo_mysql
