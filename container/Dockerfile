# vim:set ft=dockerfile:

FROM debian:latest

MAINTAINER wluisaraujo

RUN apt-get update
RUN apt-get install -y bind9

#VOLUME [ "/path", "/path1" ]
#COPY named.conf.local /etc/nginx/sites-available/default
#CMD service bind9 start

EXPOSE 53/tcp 53/udp
