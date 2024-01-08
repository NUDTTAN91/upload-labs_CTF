FROM nudttan91/base_image_nginx_php_73

LABEL Author="tan91"
LABEL GitHub="https://github.com/NUDTTAN91"
LABEL Blog="zxw-nudt.blog.csdn.net"

COPY html /var/www/html/
RUN chown www-data:www-data -R /var/www/html/

COPY php.ini /usr/local/etc/php/
RUN chmod 777 /usr/local/etc/php/php.ini

COPY file /
RUN chmod 777 /flag.sh

