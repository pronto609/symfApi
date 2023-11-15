FROM php:8.1-fpm

RUN pecl update-channels; \
    printf "\n" | pecl install redis xdebug; \
    docker-php-ext-enable redis; \