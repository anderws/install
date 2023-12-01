FROM nginx

#RUN apt-get update && apt-get install -y nginx-extras
#RUN apt-get update
#RUN apt-get install libnginx-mod-http-headers-more-filter
COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80
