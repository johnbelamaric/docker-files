FROM ubuntu:latest
MAINTAINER John Belamaric <john@belamaric.com> @johnbelamaric

RUN apt-get update && \
    apt-get -y install iputils-ping inetutils-traceroute && \
    apt-get -y install net-tools tcpdump dnsutils iproute2 && \
    apt-get -y install iputils-tracepath && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["/bin/bash"]
