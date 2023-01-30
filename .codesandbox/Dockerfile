FROM ubuntu:22.04

RUN apt-get -y update && apt-get install -y wget

# Golang
RUN cd /tmp \
    && wget https://go.dev/dl/go1.19.5.linux-amd64.tar.gz \
    && tar -C /usr/local -xzf go1.19.5.linux-amd64.tar.gz \
    && rm go1.19.5.linux-amd64.tar.gz 
    
ENV PATH=$PATH:/usr/local/go/bin
ENV GOPATH=/workspace/go