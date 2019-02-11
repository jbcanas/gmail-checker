FROM php:7.2-fpm-alpine

RUN docker-php-ext-install pdo pdo_mysql bcmath

WORKDIR /app

EXPOSE 9000
CMD ["php-fpm"]
