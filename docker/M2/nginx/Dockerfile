ARG M2_NGINX_VERSION=""
FROM nginx:${M2_NGINX_VERSION}
COPY ./M2/nginx/configs/nginx.conf /etc/nginx/nginx.conf
COPY ./M2/nginx/certificates/local.crt /etc/nginx/certificates/local.crt
COPY ./M2/nginx/certificates/local.key /etc/nginx/certificates/local.key
