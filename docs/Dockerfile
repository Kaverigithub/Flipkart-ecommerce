 FROM ubuntu:22.04 
MAINTAINER "info@gamutgurus.com"
RUN apt-get update
RUN apt-get  install -y  openjdk-8-jdk
ADD apache-tomcat-8.5.38.tar.gz /root
COPY target/gamutgurus.war /root/apache-tomcat-8.5.38/webapps
ENTRYPOINT /root/apache-tomcat-8.5.38/bin/startup.sh && bash

