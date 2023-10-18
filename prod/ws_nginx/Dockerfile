FROM nginx:mainline-alpine3.18

WORKDIR /etc/nginx

COPY ./files /etc/nginx

COPY ws_nginx.conf.prod /etc/nginx/conf.d/nginx.conf

EXPOSE 80
