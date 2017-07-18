FROM ubuntu:17.04
MAINTAINER aaron.pederson@gmail.com

RUN \
     apt-get update && \
     apt-get -y upgrade && \

     apt-get install -y build-essential && \
     apt-get install -y software-properties-common && \
     apt-get install -y fish git htop zsh && \

     rm -rf /var/lib/apt/lists/*
