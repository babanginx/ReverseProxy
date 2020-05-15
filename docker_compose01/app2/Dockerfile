FROM nginx:mainline-alpine
RUN rm /etc/nginx/conf.d/default.conf
ADD hello.conf /etc/nginx/conf.d/
ADD index.html /usr/share/nginx/html/