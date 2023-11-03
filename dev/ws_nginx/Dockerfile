FROM nginx:mainline-alpine3.18

WORKDIR /etc/nginx

COPY ./dev/ws_nginx/ws_nginx.conf.dev /etc/nginx/conf.d/nginx.conf

COPY ./project /var/www/

EXPOSE 80
