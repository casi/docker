FROM casi/debian:stretch

RUN DEBIAN_FRONTEND=noninteractive apt-get update \
    && apt-get install --no-install-recommends ruby -y \
    && gem install bundler --no-document \
    && rm -rf /var/lib/apt/lists/*

