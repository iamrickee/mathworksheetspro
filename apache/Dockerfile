FROM httpd:2.4-alpine

RUN apk update; apk upgrade;

COPY httpd.conf /usr/local/apache2/conf/httpd.conf

COPY httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf