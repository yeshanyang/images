FROM ubuntu:xenial
WORKDIR /etc/apt
RUN echo 'deb http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse' >/etc/apt/sources.list
RUN echo 'deb http://mirrors.aliyun.com/ubuntu xenial-security main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb http://mirrors.aliyun.com/ubuntu xenial-updates main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb http://mirrors.aliyun.com/ubuntu xenial-backports main restricted universe multiverse' >> /etc/apt/sources.list
RUN apt-get wget install unzip make gcc libpcre3-dev zlib1g-dev --assume-yes
wget https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/core-install.yaml
