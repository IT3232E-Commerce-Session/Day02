# Day02
# Introduction to Spring Boot with Spring Tool Suite 4.0 🚀

## Overview 📘

The Day 02 practicals introduce the basics of setting up and working with Spring Boot using Spring Tool Suite 4.0. This session focuses on creating a simple Spring Boot application and defining basic REST API endpoints.

## Topics Covered 📝

### 1. Spring Boot Setup:

Installation and configuration of Spring Tool Suite 4.0.

Creating a new Spring Boot project.

### 2. REST API Basics:

Understanding the structure of a Spring Boot project.

Creating a basic controller class.

Defining API endpoints using @RestController and @RequestMapping.

## Practical Exercise 💡

### 1. Creating a Simple Spring Boot Application

#### Problem Specification: **Develop a Spring Boot application that defines basic API endpoints to return messages.**

#### Implementation:

- Create a Spring Boot project using Spring Tool Suite 4.0.
- Define a controller class `AppController` inside the `com.example.demo.controller` package.
- Implement two REST API endpoints that return simple text responses.


## Expected Outputs 🖥️

### 1. Accessing the `/msg` endpoint:
   **URL:** `http://localhost:8080/app/msg`
   **Output:**
   ```
   Hello Springboot
   ```

### 2. Accessing the `/name` endpoint:
   **URL:** `http://localhost:8080/app/name`
   **Output:**
   ```
   My Name is Springboot
   ```