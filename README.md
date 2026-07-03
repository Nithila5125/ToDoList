# ToDoList - DevOps CI/CD Pipeline

A Java To-Do List application demonstrating a complete CI/CD pipeline using Maven, Docker, Jenkins, and Ansible.

## Tech Stack
- Language: Java (Maven build)
- Containerization: Docker
- CI/CD: Jenkins (Jenkinsfile)
- Deployment: Ansible (deploy_app.yml)
- Testing: JUnit

## Project Structure
- src/main/java - application source
- src/test/java - unit tests
- Dockerfile - container build
- Jenkinsfile - CI/CD pipeline stages
- deploy_app.yml - Ansible deployment playbook
- pom.xml - Maven configuration

## Build & Run
mvn clean package
docker build -t todolist .
docker run todolist

## CI/CD Pipeline
The Jenkins pipeline automates build, test, and deployment - compiling with Maven, running tests, building the Docker image, and deploying via Ansible.
