From php:7.2-fpm

RUN apt-get update
RUN apt-get install -y libgmp-dev
RUN docker-php-ext-install gmp
RUN docker-php-ext-install pdo pdo_mysql