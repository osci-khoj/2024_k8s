FROM ubuntu:20.04
MAINTAINER Hojin kim "khoj@osci.kr" 
RUN apt update
RUN apt install -y nginx
WORKDIR /etc/nginx 
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80