FROM nginx:alpine

RUN rm /etc/nginx/conf.d/default.conf

COPY proxy.conf /etc/nginx/conf.d/
COPY localhost.crt /etc/ssl/certs/
COPY localhost.key /etc/ssl/private/
COPY cert.pem /etc/nginx/conf.d/
COPY key.pem /etc/nginx/conf.d/