FROM debian:jessie-backports
MAINTAINER ClouDesire <dev@cloudesire.com>

RUN apt-get update && \
    apt-get install -y --force-yes --no-install-recommends openjdk-7-jre-headless && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists
