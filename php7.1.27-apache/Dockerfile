FROM php:7.1.27-apache
MAINTAINER binary4bytes@gmail.com

ADD https://getcomposer.org/installer /tmp/composer-setup.php
RUN php /tmp/composer-setup.php --install-dir=/bin --filename=composer && rm -f /tmp/composer-setup.php
