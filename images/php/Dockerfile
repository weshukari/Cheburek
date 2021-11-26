FROM php:7.2-fpm 
RUN apt-get update &&  docker-php-ext-install -j$(nproc) mysqli
# ADD php.ini /usr/local/etc/php/conf.d/40-custom.ini
WORKDIR /var/www
CMD ["php-fpm"]