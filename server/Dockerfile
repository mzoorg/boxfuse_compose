FROM ubuntu:18.04
ARG DEBIAN_FRONTEND=noninteractive
ENV CATALINA_HOME=/usr/share/tomcat9
ENV CATALINA_BASE=/var/lib/tomcat9
RUN apt update && apt install -y tomcat9 default-jdk
WORKDIR $CATALINA_HOME/bin
CMD ["./catalina.sh", "run"]