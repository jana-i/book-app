# Book App: Spring Boot, PostgreSQL, Docker, CI/CD & Kubernetes

A book catalog web application built with Spring Boot and PostgreSQL. Users can add, edit, delete, and review books. 
The project covers a complete DevOps workflow: containerization with Docker, orchestration with Docker Compose, 
a CI pipeline with GitHub Actions that publishes the image to Docker Hub, and deployment to a local Kubernetes cluster (k3d).

Features
- Add book: ISBN, title, genre, and year
- Edit book: update the details of an existing book
- Delete book: remove a book from the list
- Review: write a personal review or critique for a book


## Tech Stack

- Backend	Java, Spring Boot, Spring Data JPA, Hibernate (ORM)
- Database	PostgreSQL
- Build	Maven
- Containers	Docker (multi-stage build, Maven + OpenJDK), Docker Compose
- CI/CD	GitHub Actions, Docker Hub
- Orchestration	Kubernetes, kubectl, k3d

##What I learned
Containerizing a Spring Boot application with a multi-stage Docker build
Orchestrating an app and its database with Docker Compose
Automating image builds and publishing with GitHub Actions and repository secrets
Writing Kubernetes manifests for a stateless app (Deployment) and a stateful database (StatefulSet with a PersistentVolumeClaim)
Using ConfigMaps, Secrets, Services and Ingress, and isolating resources in a namespace
Running and debugging a local cluster with k3d and kubectl
