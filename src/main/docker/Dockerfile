FROM openjdk:8u111-jre-alpine

ADD demo-git-0.0.1-SNAPSHOT.jar /demo-alias.jar


ENTRYPOINT ["java", "-Xmx=128m", "-jar", "/demo-alias.jar"]