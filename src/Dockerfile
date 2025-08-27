FROM eclipse-temurin:17-jre
WORKDIR /app
COPY target/Shopping_Application-0.0.1-SNAPSHOT.jar myshopping-v1.0.jar
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "myshopping-v1.0.jar"]