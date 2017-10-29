# A Movie Recommendation Application written in Dropwizard

How to start the movie-recommender application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/movie-recommender-1.0-SNAPSHOT.jar server config.yaml`
1. To check that your application is running enter url `http://localhost:8080`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`

References
---

Adomavicius, Gediminas, and Alexander Tuzhilin. "Toward the next generation of recommender systems: A survey of the state-of-the-art and possible extensions." IEEE transactions on knowledge and data engineering 17, no. 6 (2005): 734-749.

