FROM openjdk:8
COPY product-catalogue.yml product-catalogue.yml

ADD target/productcatalogue-0.0.1-SNAPSHOT.jar app.jar

CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar", "server", "product-catalogue.yml"]
