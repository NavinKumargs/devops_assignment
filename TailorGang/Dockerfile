FROM openjdk:23

WORKDIR /app

COPY target/tailorgang.jar tailorgang.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","tailorgang.jar"]