FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY target/spring-petclinic-admin-server-4.0.1.jar app.jar

EXPOSE 9090

ENTRYPOINT ["java","-jar","app.jar"]
