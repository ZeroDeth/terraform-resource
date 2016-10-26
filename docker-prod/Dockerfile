FROM alpine:latest

RUN apk update  \
    && apk add ca-certificates git bash wget openssl \
    && update-ca-certificates

COPY terraform/* /usr/local/bin/
#COPY check in out /opt/resource/
