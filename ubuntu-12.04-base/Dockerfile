# Dockerfile that creates a base Ubuntu 12.04 (precise) base image that other
# containers can build on.  Includes some useful utilities (i.e., htop, screen, etc.).
FROM ubuntu:precise
MAINTAINER John Jilek <jsj@agtechnet.com>

RUN apt-get update && apt-get -y upgrade \
    && apt-get install -y --no-install-recommends \
    htop \
    screen \
    ca-certificates \
    curl \
    wget \
    openssh-server \
    openssh-client \
    && rm -rf /var/lib/apt/lists/*
