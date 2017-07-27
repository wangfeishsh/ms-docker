FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD ms-docker.jar app.jar
RUN sh -c 'touch /app.jar'
EXPOSE 9001
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
STOPSIGNAL 9