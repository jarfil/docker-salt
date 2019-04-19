FROM jarfil/salt-master-docs:fedora-29

MAINTAINER Jaroslaw Filiochowski <jarfil@gmail.com>

COPY docker-entrypoint.sh /

RUN dnf -y upgrade && \
	dnf -y --setopt=tsflags='' install \
		salt-api \
		salt-syndic && \
	dnf clean all 

RUN chmod +x \
	/docker-entrypoint.sh

EXPOSE 4505 4506

CMD /docker-entrypoint.sh
