FROM markymark1/ubuntu-tini:xenial-1
MAINTAINER mkelly28@tcd.ie

RUN apt-get update && apt-get install --no-install-recommends -y openjdk-8-jdk

#Place bash scripts in this folder - if you need it - agents etc
ADD utils /java-utils
ENV PATH ${PATH}:/${JAVA_HOME}/bin:/java-utils

CMD ["java", "-version"]
