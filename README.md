# 🚀 Maven SpringBoot Employee API

## 📌 Project Overview

**Maven SpringBoot Employee API** is a simple Java web application built using **Spring Boot** and **Maven** that demonstrates how a backend service is built, packaged, and executed as a standalone application.

This project showcases the complete lifecycle of a production-style application:

* Build using Maven
* Package as executable JAR
* Run embedded server
* Handle HTTP requests
* Return browser responses

It is designed to demonstrate practical understanding of **application build, runtime behavior, and deployment flow**, which are essential skills for backend and DevOps environments.

---

## ⚙️ Tech Stack

* Java 17
* Spring Boot
* Maven
* Embedded Tomcat Server

---

## 📂 Project Structure

```
employee-api
 ├── pom.xml
 └── src
      ├── main/java/com/example/employee
      │        ├── EmployeeApiApplication.java
      │        └── HelloController.java
      └── main/resources
               └── application.properties
```

---

## ▶️ How to Run Application

### Build Project

```
mvn package
```

### Run Application

```
java -jar target/employee-api-1.0.0.jar
```

---

## 🌐 Access Endpoint

Open in browser:

```
http://localhost:8080/hello
```

**Output**

```
Hello Employee Service Running
```

---

## 🎯 What This Project Demonstrates

This project proves understanding of:

* Maven build lifecycle
* Dependency management
* Packaging Java applications
* Running executable JAR services
* Embedded server execution
* REST endpoint handling

---

## 💼 Why This Project Matters

This repository demonstrates practical knowledge required in real-world development and DevOps environments, including:

* Build automation
* Application packaging
* Runtime execution
* Service testing

---

## 👨‍💻 Author

Developed as part of hands-on practice to strengthen backend and DevOps fundamentals.

