FROM php:7.3-fpm
COPY ./src/backend/ /app
WORKDIR /app
RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y git
RUN docker-php-ext-install pdo_mysql