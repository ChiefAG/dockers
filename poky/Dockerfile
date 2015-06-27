# Dockerfile that creates a container with development dependencies and scm support
FROM agtech/dev-deps
MAINTAINER John Jilek <jsj@agtechnet.com>

RUN apt-get update && apt-get -y upgrade

RUN mkdir -p /shared

RUN mkdir -p /opt/yocto \
    && su -c "cd /opt/yocto && git clone git://git.yoctoproject.org/poky --branch fido" root

ENTRYPOINT ["/bin/bash"]

#EOF
