# devops-java-app-jenkins-docker
End-to-end CI/CD pipeline for a Java application using Jenkins, Maven, Docker, and Linux. Derived and enhanced from an open-source DevOps practice project.

# DevOps Java App – Jenkins & Docker CI/CD Pipeline

## Overview
This project demonstrates an end-to-end CI/CD pipeline for a Java web application using Jenkins, Maven, Docker, and Tomcat on a Linux environment. The primary focus of this project is DevOps automation rather than application complexity.

## Architecture
- GitHub – Source code management
- Jenkins – CI/CD automation
- Maven – Build and dependency management
- Docker – Containerization
- Tomcat – Application server
- Linux – Deployment environment

## CI/CD Workflow
1. Developer pushes code to GitHub
2. Jenkins triggers the pipeline
3. Maven builds the Java application
4. Docker image is created
5. Application is deployed as a container
6. Application is accessed via browser

## What I Implemented
- CI/CD pipeline using Jenkins (pipeline-as-code)
- Automated Maven build process
- Dockerized Java application
- Container-based deployment on Linux
- Build and deployment validation

## Tools & Technologies
- Java
- Maven
- Jenkins
- Docker
- Tomcat
- Linux
- GitHub

## Challenges Faced
- Jenkins permission and workspace issues
- Docker port conflicts
- Maven dependency resolution errors

## Future Enhancements
- AWS EC2 deployment
- Kubernetes orchestration
- GitHub Actions pipeline
- Security scanning (SonarQube, Trivy)
- Monitoring with Prometheus & Grafana

## Attribution
This project is a derived and enhanced implementation inspired by an open-source DevOps practice project.  
Original reference: https://github.com/harish303118/DevOps-Projects
