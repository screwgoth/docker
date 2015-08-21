FROM ubuntu:14.04.3

MAINTAINER Raseel Bhagat <raseelbhagat@gmail.com>

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y ca-certificates inotify-tools build-essential git openssh-server unrar unzip wget && \
    apt-get clean

EXPOSE 22
