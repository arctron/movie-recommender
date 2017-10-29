# movie-recommender

How to start the movie-recommender application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/movie-recommender-1.0-SNAPSHOT.jar server config.yaml`
1. To check that your application is running enter url `http://localhost:8080`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`