FROM debian:jessie
MAINTAINER Falco Vennedey "docker@vennedey.net"

# Add repository & key
ADD https://repo.saltstack.com/apt/debian/8/amd64/latest/SALTSTACK-GPG-KEY.pub /tmp/SALTSTACK-GPG-KEY.pub
RUN apt-key add /tmp/SALTSTACK-GPG-KEY.pub && rm /tmp/SALTSTACK-GPG-KEY.pub \
	&&  echo "deb http://repo.saltstack.com/apt/debian/8/amd64/latest jessie main" >> /etc/apt/sources.list \
	&& apt-get update
