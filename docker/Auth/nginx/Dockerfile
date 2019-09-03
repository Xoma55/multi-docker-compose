ARG AUTH_NGINX_VERSION=""
FROM nginx:${AUTH_NGINX_VERSION}
COPY ./Auth/nginx/configs/nginx.conf /etc/nginx/nginx.conf
COPY ./Auth/nginx/certificates/local.crt /etc/nginx/certificates/local.crt
COPY ./Auth/nginx/certificates/local.key /etc/nginx/certificates/local.key
