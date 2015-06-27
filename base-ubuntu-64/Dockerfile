# Dockerfile that creates a base Ubuntu 14.04 (trusty) base image that other
# containers can build on.  Includes some useful utilities (i.e., htop, screen, etc.).
FROM ubuntu:trusty
MAINTAINER John Jilek <jsj@agtechnet.com>

RUN apt-get update \
    && apt-get install -y \
    htop \
    screen \
    ca-certificates \
    curl \
    wget \
    && rm -rf /var/lib/apt/lists/*
