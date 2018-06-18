FROM ubuntu:18.04

ENV JAV8_VERSION=8u171-1~webupd8~0

# Install Java.
RUN \
    apt update && \
    apt upgrade -y && \
    apt install -y software-properties-common && \
    echo oracle-java8-installer shared/accepted-oracle-license-v1-1 select true | debconf-set-selections && \
    add-apt-repository -y ppa:webupd8team/java && \
    apt-get install -y oracle-java8-installer=$JAV8_VERSION oracle-java8-unlimited-jce-policy=$JAV8_VERSION oracle-java8-set-default=$JAV8_VERSION && \
    rm -rf /var/lib/apt/lists/* && \
    rm -rf /var/cache/oracle-jdk8-installer

# Define working directory.
WORKDIR /data

# Define commonly used JAVA_HOME variable
ENV JAVA_HOME /usr/lib/jvm/java-8-oracle

# Define default command.
CMD ["bash"]