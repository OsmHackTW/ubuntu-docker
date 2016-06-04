FROM ubuntu:trusty
MAINTAINER Rex Tsai <rex.cc.tsai@gmail.com>

ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update \
        && apt-get dist-upgrade -y \
        && apt-get install -y vim iputils-ping netcat-openbsd
