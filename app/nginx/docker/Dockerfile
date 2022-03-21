FROM ubuntu:20.04
EXPOSE 80
RUN mkdir -p /nginx && apt update && apt install -y nginx
WORKDIR /nginx
CMD ["nginx","-g","daemon off;"]
