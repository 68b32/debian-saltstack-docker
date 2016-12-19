FROM debian-saltstack-base
MAINTAINER Falco Vennedey "docker@vennedey.net"

ADD https://repo.saltstack.com/apt/debian/8/amd64/latest/SALTSTACK-GPG-KEY.pub /tmp/SALTSTACK-GPG-KEY.pub
RUN apt-get install --no-install-recommends --no-install-suggests -y salt-master

CMD /bin/bash
