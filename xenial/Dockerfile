FROM ubuntu:xenial
MAINTAINER Rex Tsai <rex.cc.tsai@gmail.com>

ENV DEBIAN_FRONTEND=noninteractive
RUN sed -e s%http://archive.ubuntu.com/ubuntu/%mirror://mirrors.ubuntu.com/mirrors.txt% -i /etc/apt/sources.list \
        && apt-get update \
        && apt-get dist-upgrade -y \
        && apt-get install -y vim
