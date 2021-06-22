FROM ubuntu:18.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt update && apt install -y \
    git \
    maven \
    default-jdk
WORKDIR /opt/java-projects
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
WORKDIR ./boxfuse-sample-java-war-hello
RUN mvn package