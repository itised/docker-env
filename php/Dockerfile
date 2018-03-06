From php:7.2-fpm

RUN apt-get update
RUN apt-get install -y libgmp-dev libmcrypt-dev
RUN docker-php-ext-install gmp
RUN docker-php-ext-install -j$(nproc) iconv mcrypt
RUN docker-php-ext-install pdo pdo_mysql