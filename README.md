# CST8915 Lab 4 – Docker

**Student:** Kaveh Kheir Abadi  
**Course:** CST8915 – Full-stack Cloud-native Development  
**Semester:** Fall 2026

## Lab Status

Completed Docker Lab 4, including Docker images, containers, image layers, container writable layers, Docker Compose, and scaling.

## Demo Video

[Watch Lab 4 Demo Video](https://youtu.be/4ofKoUK7Y_E)

The video demonstrates Part 6: Docker Compose with Flask and Redis, including container management and scaling.

## Reflection Questions

### 1. What is the difference between a Docker image and a container?

A Docker image is a template that includes the application and its dependencies. A container is a running instance of an image.

### 2. How do Docker image layers improve efficiency?

Docker images use layers that can be reused and cached. This makes building images faster and saves storage space.

### 3. Why does each container have its own writable layer?

Each container has its own writable layer to keep changes separate. Changes inside one container do not affect other containers created from the same image.

### 4. What are the benefits of Docker Compose?

Docker Compose makes it easier to run and manage multiple containers using one YAML file. In this lab, I used it to run Flask and Redis together, manage containers, and scale the Flask service.
