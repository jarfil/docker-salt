FROM debian:stretch

MAINTAINER Jaroslaw Filiochowski <jarfil@gmail.com>

RUN apt-get -y update && \
	apt-get -y upgrade && \
	apt-get -y install \
		gnupg \
		wget && \
	wget -O - https://repo.saltstack.com/py3/debian/9/amd64/latest/SALTSTACK-GPG-KEY.pub | apt-key add - && \
	apt-get -y purge \
		gnupg \
		wget && \
	apt-get -y autoremove && \
	apt-get clean && \
	rm -rf /var/lib/apt/lists/

COPY saltstack.list /etc/apt/sources.list.d/saltstack.list

RUN apt-get -y update && \
	apt-get -y upgrade && \
	apt-get -y install \
		salt-common && \
	apt-get -y autoremove && \
	apt-get clean && \
	rm -rf /var/lib/apt/lists/
