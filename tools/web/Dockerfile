FROM nginx

LABEL maintainer="morningspace@yahoo.com"

RUN \
# install packages
    apt-get update && \
    apt-get install --no-install-recommends --no-install-suggests -y \
    inetutils-ping iproute2 curl && \
    rm -rf /var/lib/apt/lists/*
