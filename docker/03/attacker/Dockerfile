FROM debian:stable-slim

RUN apt-get update && \
    apt-get -y upgrade && \
    DEBIAN_FRONTEND=noninteractive \
    apt-get -y install net-tools nmap && \
    rm -rf /var/lib/apt/lists*

RUN mkdir /root/workspace
WORKDIR /root/workspace
