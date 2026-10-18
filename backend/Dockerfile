FROM eclipse-temurin:17-jre
WORKDIR /app
# Le jar est produit par "mvn package" (stage Package Backend du pipeline)
COPY target/*.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]
