FROM nginx:latest
RUN apt-get update && apt-get install -y procps
RUN mkdir -p /home/app/staticfiles
RUN rm /etc/nginx/conf.d/default.conf