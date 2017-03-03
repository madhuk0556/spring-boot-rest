FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
COPY gs-spring-boot-docker-0.1.0.jar /
RUN sh -c 'touch /gs-spring-boot-docker-0.1.0.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /" ]

