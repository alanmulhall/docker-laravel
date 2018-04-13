FROM nginx:1.12

ADD ./docker/web/vhost.conf /etc/nginx/conf.d/default.conf

RUN usermod -u 1000 www-data

WORKDIR /var/www
