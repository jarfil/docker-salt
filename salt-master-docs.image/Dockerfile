FROM jarfil/salt-master:fedora-29

MAINTAINER Jaroslaw Filiochowski <jarfil@gmail.com>

COPY docker-entrypoint.sh /

RUN dnf -y upgrade && \
	dnf -y --setopt=tsflags='' install \
		man-db && \
	dnf -y --setopt=tsflags='' reinstall \
		salt \
		salt-minion \
		salt-master \
		salt-ssh \
		salt-cloud && \
	dnf clean all 

RUN chmod +x \
	/docker-entrypoint.sh

EXPOSE 4505 4506

CMD /docker-entrypoint.sh
