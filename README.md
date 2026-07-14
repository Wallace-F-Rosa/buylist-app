# Buylist App

Buylist App is a study case project for learning Spring Boot, REST APIs, and microservices-style architecture. The goal is to build a simple but realistic application for managing grocery buylists while exploring backend design, service boundaries, and application structure.

## Purpose

This project is mainly a learning exercise. It is focused on understanding how to:

- build a Spring Boot backend
- create and manage REST endpoints
- work with authentication and protected APIs
- structure a small application around multiple modules
- explore the foundations of a microservices-oriented design

## What the app does

Buylist App helps users manage grocery buylists and related items, with the main idea of practicing real backend development in a practical context.

## Project structure

The repository is divided into three main parts:

- buy-list-api: the Spring Boot backend responsible for the business logic
- buylist-web: the Angular frontend for interacting with the app
- buylist-notify: a future service intended for sending reminders and notifications

## Learning goals

- Learn how to build a backend with Spring Boot
- Understand how to expose and consume APIs
- Practice modular application development
- Explore how services can evolve into a microservices architecture
- Experiment with notification features in a future step

## Roadmap

### Current progress

- [x] Create the repository structure for the full project
- [x] Build a Spring Boot API for managing buylists and ingredients
- [x] Add authentication and protected API access
- [x] Provide API documentation with Swagger
- [x] Create the Angular frontend foundation

### Next steps

- [ ] Implement the notification service as a separate module
- [ ] Add reminder scheduling for buylist dates
- [ ] Support email notifications
- [ ] Support WhatsApp notifications
- [ ] Improve the web interface and user experience

## Note

This project is not intended to be a production-ready product first; it is primarily a hands-on study case for improving backend and architecture skills.
