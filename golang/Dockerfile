FROM alpine:3.3
MAINTAINER Stefan Obradovic <me@stefano.id.au>

RUN apk add -U curl git mercurial bzr go && rm -rf /var/cache/apk/*

ENV GOROOT /usr/lib/go
ENV GOPATH /gopath
ENV GOBIN /gopath/bin
ENV PATH $PATH:$GOROOT/bin:$GOPATH/bin
