FROM ubuntu:18.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt update && apt install -y tomcat9 default-jdk
WORKDIR $CATALINA_HOME/bin
CMD ["catalina.sh", "run"]