# FitFlow Redesign

## IT3060 – Human Computer Interaction

FitFlow is a cross-platform fitness application redesign that provides personalized workout planning, nutrition tracking, progress monitoring, and social fitness features.

This repository contains the technology analysis, technology comparison matrix, high-level system architecture, and supporting documentation prepared for Lab Exercise 05.

## Selected Technology Stack

| Component               | Selected Technology     |
| ----------------------- | ----------------------- |
| Frontend                | Flutter (Dart)          |
| Main Backend            | Node.js + NestJS        |
| AI Microservice         | Python + FastAPI        |
| Database                | PostgreSQL              |
| Authentication          | Firebase Authentication |
| Caching                 | Redis                   |
| Real-Time Communication | WebSockets              |

## Key Features

* Personalized workout plans
* AI-powered workout recommendations
* Nutrition tracking
* Fitness progress monitoring
* Social sharing and community features
* Real-time notifications and updates
* Secure user authentication
* Cross-platform support for Android, iOS, and Web

## Repository Structure

```text
fitflow-redesign/
│
├── frontend/
├── backend/
├── ai-service/
├── docs/
│   ├── technology-comparison.md
│   ├── weighted-matrix.md
│   ├── architecture.md
│   ├── architecture-diagram.png
│   └── ADR-001.md
│
├── README.md
└── .gitignore
```

## Architecture Overview

The FitFlow system uses Flutter as the cross-platform frontend and Node.js with NestJS as the main backend. A separate Python/FastAPI microservice handles AI-related functionality. PostgreSQL is used as the primary database, while Firebase Authentication provides user authentication.

Redis is used as a caching layer and WebSockets support real-time communication.

## Documentation

* [Technology Comparison](docs/technology-comparison.md)
* [Weighted Technology Matrix](docs/weighted-matrix.md)
* [System Architecture](docs/architecture.md)
* [Architecture Decision Record](docs/ADR-001.md)

## Academic Context

**Course:** IT3060 – Human Computer Interaction
**Academic Year:** 2026
**Student:** J.S Gunasekara
**Student ID:** IT23817494
