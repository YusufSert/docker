FROM ubuntu

RUN apt-get -yqq update
RUN apt-get -yqq install wget

VOLUME ["/var/lib/tomcat7/webapps/"]

WORKDIR /var/lib/tomcat7/webapps/

ENTRYPOINT ["wget"]
CMD ["--help"]


