FROM ubuntu:22.10
LABEL maintainer="sebastian@sommerfeld.io"

RUN apt-get update \
    && apt-get install -y --no-install-recommends jq=1.6-2.1ubuntu3 \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
