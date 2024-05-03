FROM php:8.2-apache

#ADD https://github.com/mlocati/docker-php-extension-installer/releases/latest/download/install-php-extensions /usr/local/bin/

#RUN chmod +x /usr/local/bin/install-php-extensions && \ install-php-extensions pdo_pgsql intl

#COPY install-php-extensions /tmp/install-php-extensions
#RUN chmod +x /tmp/install-php-extensions pdo_pgsql intl

ADD https://github.com/mlocati/docker-php-extension-installer/releases/download/4.0.2/install-php-extensions /usr/local/bin/

RUN chmod +x /usr/local/bin/install-php-extensions
RUN install-php-extensions pdo_pgsql intl