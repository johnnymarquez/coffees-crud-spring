# CoffeesCRUDSpring
Example REST coffees CRUD microservice developed with Java, Spring Framework, JPA and H2.

Template developed from [SpringBootUpAndRunning](https://github.com/mkheck/SpringBootUpAndRunning)

# Getting Started

## Windows
### Compile Code
	./mvnw.cmd clean compile -e

### Test Code
	./mvnw.cmd clean test -e

### Jar Code
	./mvnw.cmd clean package -e

### Run Jar
	Local:      ./mvnw.cmd spring-boot:run 
	Background: nohup bash mvnw.cmd spring-boot:run &

### Open Application
	http://localhost:8080/coffees

## Linux

### Compile Code
	./mvnw clean compile -e

### Test Code
	./mvnw clean test -e

### Jar Code
	./mvnw clean package -e

### Run Jar
	Local:      ./mvnw spring-boot:run 
	Background: nohup bash mvnw spring-boot:run &
  
### Open Application
	http://localhost:8080/coffees

# Docker

### Docker Build
	docker build -t demo .
	
### Docker run
	docker run -d -p 8080:8080 demo

### This Project can be integrated with [CI/CD example pipeline](https://github.com/johnnymarquez/CICD-Pipeline-Jenkins). 
