FROM nginx:latest

MAINTAINER David Belicza "87.bdavid@gmail.com"

COPY ./conf.d /etc/nginx/conf.d
#RUN mkdir /var/www/magento2
#COPY ./www/magento2/. /var/www/magento2
#Run chown -R www-data: /var/www


WORKDIR /var/www/

CMD service nginx restart \
    && /bin/bash
