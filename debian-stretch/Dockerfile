FROM debian:stretch

RUN DEBIAN_FRONTEND=noninteractive apt-get update \
    && apt-get install --no-install-recommends curl -y \
    && rm -rf /var/lib/apt/lists/*

