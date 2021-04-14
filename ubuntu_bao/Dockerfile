FROM ubuntu:20.04
RUN apt update
RUN apt install -y net-tools
RUN apt install -y traceroute
RUN apt install -y curl
RUN apt install -y nano
RUN apt install -y mysql-client
RUN apt install -y software-properties-common dirmngr apt-transport-https lsb-release ca-certificates
RUN add-apt-repository ppa:redislabs/redis
RUN apt update
RUN apt install -y redis 
RUN apt install -y tmux 
RUN apt install -y iputils-ping 
COPY ./kubectl /usr/bin/
COPY ./helm /usr/bin/
