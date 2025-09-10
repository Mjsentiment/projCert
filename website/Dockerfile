FROM php:7.4-apache

# Optional: enable Apache rewrite module
RUN a2enmod rewrite

# Copy your app into the web root
COPY . /var/www/html/

# Set working directory
WORKDIR /var/www/html
