FROM ubuntu:16.04
LABEL env=hr
RUN apt-get update
RUN apt-get install -y nginx
RUN echo "Hi, I am in your container" \ >/var/www/html/index.html
ENV TARGET_DIR=/opt/app
WORKDIR $TARGET_DIR
ENTRYPOINT ["/usr/sbin/nginx"]
CMD ["-h"]
EXPOSE 80
