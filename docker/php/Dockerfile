FROM php:8.1-fpm

RUN pecl install redis-5.3.4 \
    && pecl install xdebug-3.1.2 \
    && docker-php-ext-enable redis xdebug
