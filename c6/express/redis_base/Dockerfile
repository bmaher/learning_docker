FROM ubuntu:trusty
MAINTAINER Brian Maher "brianmaher@gmail.com"

RUN apt-get -qq update
RUN apt-get -qq install software-properties-common python-software-properties
RUN add-apt-repository ppa:chris-lea/redis-server
RUN apt-get -qq update
RUN apt-get -qq install redis-server redis-tools

VOLUME [ "/var/lib/redis", "/var/log/redis" ]

EXPOSE 6379
CMD []
