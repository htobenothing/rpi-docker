FROM arm32v7/openjdk:slim

MAINTAINER htobenothing
ENV ZOOKEEPER_VERSION 3.4.9


RUN apt-get update && apt-get -y install curl gpg

ENV DEBIAN_FRONTEND noninteractive

RUN curl -sSL https://get.docker.com | sh

