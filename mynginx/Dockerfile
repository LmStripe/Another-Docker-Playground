FROM ubuntu
LABEL maintainer="ikambarov@yahoo.com"
RUN apt-get update && apt-get install -y nginx
EXPOSE 80 443
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]

