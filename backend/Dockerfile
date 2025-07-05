# Imagen base PHP con Apache
FROM php:8.3-apache

# Instalar extensiones necesarias
RUN docker-php-ext-install mysqli pdo pdo_mysql && a2enmod rewrite

# Copiar el código de tu proyecto al contenedor
COPY . /var/www/html/
 