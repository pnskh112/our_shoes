FROM ubuntu

RUN ["apt-get", "update"]
RUN ["apt-get", "install", "-y", "vim"]

FROM nginx
COPY nginx.conf /etc/nginx/conf.d/app.conf