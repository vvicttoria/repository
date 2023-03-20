FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
RUN mkdir /var/log/nginx/opt/
COPY conf/nginx.conf /etc/nginx/conf.d