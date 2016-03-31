FROM centos:7
MAINTAINER Mario Mohr <mohr.mario@gmail.com>

ENV JAVA_VERSION 8u77
ENV BUILD_VERSION b03

# Upgrading system
RUN yum -y update && \
    yum -y install wget && \
    wget --no-cookies --no-check-certificate --header "Cookie: oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/$JAVA_VERSION-$BUILD_VERSION/jdk-$JAVA_VERSION-linux-x64.rpm" -O /tmp/jdk-8-linux-x64.rpm && \
    yum -y install /tmp/jdk-8-linux-x64.rpm && \
    rm -f /tmp/jdk-8-linux-x64.rpm && \
    yum clean all

ENV JAVA_HOME /usr/java/latest
