FROM php:7.0-apache
COPY php.ini /usr/local/etc/php/
RUN apt-get update \
  && apt-get install -y libmcrypt-dev \
  && docker-php-ext-install pdo_mysql mysqli mbstring iconv mcrypt
