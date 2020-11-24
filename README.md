# Vivo Secure Chat Application

# Technologies used in this project

- Spring Boot
- Spring Data (JPA / Cassandra / Redis)
- Spring Security
- Spring WebSocket
- Spring Session
- Cassandra
- Redis
- RabbitMQ
- MySQL
- JUnit, Mockito and TestContainers (spin up Docker containers for Integration Tests)
- Thymeleaf, JQuery and Bootstrap
- Apache Maven (Surefire and Failsafe plugins)

# Setting up this project locally

> **Note:**
The fastest way to bootstrap this application locally is using **Docker** and **Docker Compose**. 

1. Clone this repository

2. Enter the repository directory:
```shell
$ cd ebook-chat-app-spring-websocket-cassandra-redis-rabbitmq
```

3. Set up the dependencies (Cassandra, Redis, MySQL and RabbitMQ with STOMP support):
```shell
$ docker-compose -f docker-compose/dependencies.yml up
```

5. Navigate to `http://localhost:8080` create your own Vivo account

