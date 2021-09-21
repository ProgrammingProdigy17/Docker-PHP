FROM CameronS/php:7.1-varnish
MAINTAINER CameronS <CameronS@gmail.com>

COPY xdebug.ini /usr/local/etc/php/conf.d/xdebug.ini
RUN pecl install xdebug && docker-php-ext-enable xdebug
