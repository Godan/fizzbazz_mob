FROM php:7.0-apache
ADD php.ini /usr/local/etc/php/

RUN php -r "readfile('https://getcomposer.org/installer');" | php && \
    mv composer.phar /usr/local/bin/composer
