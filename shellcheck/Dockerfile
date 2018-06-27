FROM ubuntu:18.04
RUN apt-get -y update \
    && apt-get -y --no-install-recommends install make=4.1-9.1ubuntu1 shellcheck=0.4.6-1 \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
