FROM openjdk:8
WORKDIR /app
ADD target/stockmanager-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8010
CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar", "server"]
