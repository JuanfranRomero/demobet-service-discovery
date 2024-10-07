This micro-service has the unique responsibility to act as a server to automatically register and discover instances of the architecture's micro-services. In this way, these final micro-services (clients) will ask this server for the other micro-services based on their IDs.

Technologies used:
* Spring Boot 3.3.4 with Java 17
* Spring Cloud Eureka Server
* Docker
