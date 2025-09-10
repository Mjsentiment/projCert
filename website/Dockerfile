FROM devopsedu/webapp

WORKDIR /var/www/html
RUN rm -f /var/www/html/index.html
COPY . /var/www/html

EXPOSE 80
CMD ["apache2-foreground"]
