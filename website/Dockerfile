#FROM php:8.2-apache

# Optional: enable Apache rewrite module
#RUN a2enmod rewrite

# Copy your app into the web root
#COPY . /var/www/html/

# Set working directory
#WORKDIR /var/www/html

#CMD ["apache2-foreground"]
FROM php:8.2-cli
WORKDIR /var/www/html
COPY . /var/www/html
CMD ["php", "-S", "0.0.0.0:80", "-t", "/var/www/html"]
