FROM ubuntu:latest
MAINTAINER Luke Brady

RUN apt-get update
RUN apt-get install -y git
RUN apt-get install -y nodejs

RUN git init
RUN git clone https://github.com/lbrad23105/kibana-portal

RUN node ./kibana-portal/server.js