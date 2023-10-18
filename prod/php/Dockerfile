FROM php:8.1-fpm-alpine

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

ADD  ./prod/php/php.ini /usr/local/etc/php/conf.d/40-custom.ini

COPY ./project /var/www/

WORKDIR /var/www/

CMD ["php-fpm"]
