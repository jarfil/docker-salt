FROM jarfil/salt-common:fedora-32

MAINTAINER Jaroslaw Filiochowski <jarfil@gmail.com>

COPY docker-entrypoint.sh /

RUN dnf -y upgrade && \
	dnf -y install \
		salt-minion && \
	dnf clean all 

RUN chmod +x \
	/docker-entrypoint.sh

CMD /docker-entrypoint.sh
