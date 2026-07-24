FROM ubuntu:24.04

RUN apt-get update && \
    apt-get install -y nginx && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["nginx", "-g", "daemon off;"]
