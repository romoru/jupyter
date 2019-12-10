# https://github.com/tianon/docker-brew-ubuntu-core/commit/3c462555392cb188830b7c91e29311b5fad90cfe
# ARG BASE_IMAGE=jupyterhub/jupyterhub
ARG BASE_IMAGE=ubuntu:latest
FROM $BASE_IMAGE

RUN apt-get update 
RUN apt-get -y install python3.7

RUN apt-get -y install npm

RUN npm install -g configurable-http-proxy

# RUN python3 -m pip3.7 install json

# RUN python3 -m pip3 install jupyterhub

# RUN python3 -m pip3 install --upgrade notebook

# CMD ["jupyterhub","--no-ssl"]

ENTRYPOINT ["/bin/sh", "-c", "while :; do sleep 10; done"]