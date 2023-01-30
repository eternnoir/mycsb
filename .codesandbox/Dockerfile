FROM ubuntu:22.04

# Golang
RUN cd /tmp && \
    wget https://go.dev/dl/go1.19.5.linux-amd64.tar.gz && \
    rm -rf /usr/local/go && tar -C /usr/local -xzf go1.19.5.linux-amd64.tar.gz && \
    rm go1.19.5.linux-amd64.tar.gz