# Dockerfile that creates a node container with dev-depencencies suitable as a base for a build engine
FROM agtech/node-0.12.5
MAINTAINER John Jilek <jsj@agtechnet.com>

RUN npm install -g bower contextify jscs jshint node-gyp requirejs
RUN npm cache clear

#EOF
