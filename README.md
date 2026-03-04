🚀 Jenkins CI Pipeline with Maven and Spring Boot

📌 Project Overview
This project demonstrates a **Continuous Integration (CI) pipeline using Jenkins integrated with GitHub**. The application is a simple **Spring Boot Employee API** built using **Maven**, and Jenkins automatically builds the project whenever the pipeline runs.

The pipeline reads the **Jenkinsfile directly from the GitHub repository** and executes multiple stages to build the application and generate the final artifact.

This project shows how modern DevOps workflows automate the process of:

Pulling source code from GitHub
Building the project using Maven
Running automated tests
Packaging the application as an executable JAR artifact

It demonstrates a practical **CI pipeline workflow used in real DevOps environments**.

⚙️ Tech Stack
Java 17
Spring Boot
Maven
Jenkins
Git
GitHub

📂 Project Structure
jenkins-ci
├── Jenkinsfile
├── pom.xml
└── src
├── main/java/com/example/employee
│        ├── EmployeeApiApplication.java
│        └── HelloController.java
└── main/resources
└── application.properties

⚙️ Jenkins Pipeline Stages

The Jenkins pipeline defined in the **Jenkinsfile** contains the following stages:

Checkout
Pulls the source code from the GitHub repository.

Build
Compiles the application using Maven.

Test
Runs project tests using Maven.

Package
Packages the application and generates the final executable **JAR artifact**.

Example pipeline workflow:

GitHub Repository
↓
Jenkins Pipeline
↓
Checkout Source Code
↓
Build (mvn compile)
↓
Test (mvn test)
↓
Package (mvn package)
↓
Artifact Generated (.jar)

▶️ How to Run Application Manually

Build the project

mvn package

Run the application

java -jar target/employee-api-1.0.jar

🌐 Access Endpoint

Open in browser:

http://localhost:8080/

Example Response

Welcome to Employee API - Jenkins CI Pipeline Working!

🎯 What This Project Demonstrates

This project demonstrates practical knowledge of:

Jenkins CI pipeline creation
GitHub integration with Jenkins
Pipeline as Code using Jenkinsfile
Maven build lifecycle
Automated build, test, and packaging process
Artifact generation in CI pipeline

💼 Why This Project Matters

This repository demonstrates how DevOps engineers automate application builds using **Continuous Integration pipelines**. It reflects real-world practices used in modern software development environments.

The project highlights:

Automated CI pipeline execution
Source control integration with Jenkins
Build automation using Maven
Artifact generation for deployment pipelines

👨‍💻 Author
Developed as part of hands-on practice to strengthen **AWS, DevOps, and CI/CD pipeline skills**.
