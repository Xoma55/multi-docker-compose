ARG AUTH_PHP_VERSION=""
FROM php:${AUTH_PHP_VERSION:+${AUTH_PHP_VERSION}-}fpm-alpine

RUN apk update; \
    apk upgrade;

#RUN docker-php-ext-install mysqli
#RUN docker-php-ext-install pdo pdo_mysql
