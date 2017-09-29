FROM java:8
VOLUME /tmp
ADD gs-accessing-mongodb-data-rest-0.1.0.jar app.jar
EXPOSE 9044
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
