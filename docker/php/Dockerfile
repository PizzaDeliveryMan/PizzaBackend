FROM php:7.1-fpm

# Install Debian packages and PHP extensions
RUN docker-php-ext-install -j$(nproc) pdo_mysql

WORKDIR /app
