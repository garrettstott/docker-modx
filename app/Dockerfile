FROM php:7-apache
COPY src/ /var/www/html/
RUN find /var/www/html/ -type d -exec chmod 755 {} \; &&\
    find /var/www/html/ -type f -exec chmod 644 {} \; &&\
    mkdir /var/www/html/core/cache \; &&\
    chmod -R 777 /var/www/html/core/*
EXPOSE 8080

