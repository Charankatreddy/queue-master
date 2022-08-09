FROM weaveworksdemos/msd-java:jre-latest

WORKDIR /usr/src/app
COPY ./target/*.jar ./app.jar

ENTRYPOINT ["/usr/local/bin/java.sh","-jar","./app.jar", "--port=80"]
