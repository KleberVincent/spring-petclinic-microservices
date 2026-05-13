FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY target/spring-petclinic-visits-service-4.0.1.jar app.jar

EXPOSE 8083

ENTRYPOINT ["java","-jar","app.jar"]
