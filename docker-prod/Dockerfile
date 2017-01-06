FROM alpine:latest

RUN apk update && \
    apk add ca-certificates git bash openssh-client && \
    ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts

COPY terraform/* /usr/local/bin/
COPY check in out /opt/resource/
