FROM nginx:mainline-alpine3.18

WORKDIR /etc/nginx

COPY ./prod/ws_nginx/ws_nginx.conf.prod /etc/nginx/conf.d/nginx.conf

COPY ./project /var/www/
EXPOSE 80
