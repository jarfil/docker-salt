FROM jarfil/salt-master-mini:fedora-29

MAINTAINER Jaroslaw Filiochowski <jarfil@gmail.com>

COPY docker-entrypoint.sh /

RUN dnf -y upgrade && \
	dnf -y install \
		salt-minion \
		salt-ssh \
		salt-cloud && \
	dnf clean all 

RUN chmod +x \
	/docker-entrypoint.sh

EXPOSE 4505 4506

CMD /docker-entrypoint.sh
