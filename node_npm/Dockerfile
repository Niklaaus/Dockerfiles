FROM ubuntu:14.04

MAINTAINER Allfather Zeus <allfather.zeus@gmail.com>

RUN \
apt-get update && \
apt-get install -y git build-essential curl wget software-properties-common && \
wget https://nodejs.org/dist/v8.12.0/node-v8.12.0-linux-x64.tar.xz && \
sudo tar -xf node-v8.12.0-linux-x64.tar.xz --directory /usr/local --strip-components 1 && \
node -v && \
npm -v

