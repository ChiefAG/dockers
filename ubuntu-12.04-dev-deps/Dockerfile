# Dockerfile that creates a container with development dependencies and scm support
FROM agtech/ubuntu-12.04-base
MAINTAINER John Jilek <jsj@agtechnet.com>

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    bzr \
    git \
    git-core \
    mercurial \
    subversion \
    openssh-client \
    gawk \
    diffstat \
    unzip \
    texinfo \
    chrpath \
    autoconf \
    build-essential \
    imagemagick \
    libbz2-dev \
    libcurl4-openssl-dev \
    libevent-dev \
    libffi-dev \
    libglib2.0-dev \
    libjpeg-dev \
    liblzma-dev \
    libmagickcore-dev \
    libmagickwand-dev \
    libmysqlclient-dev \
    libncurses-dev \
    libpq-dev \
    libreadline-dev \
    libsqlite3-dev \
    libssl-dev \
    libxml2-dev \
    libxslt-dev \
    libyaml-dev \
    zlib1g-dev \
&& rm -rf /var/lib/apt/lists/*
