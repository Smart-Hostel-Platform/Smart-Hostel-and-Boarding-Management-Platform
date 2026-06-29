# Smart-Hostel-and-Boarding-Management-Platform

A comprehensive hostel and boarding management platform for student accommodation administration.

## Project Overview

This platform digitizes core hostel administration activities including:
- Room allocation and occupancy management
- Complaint and maintenance tracking
- Visitor management
- Payment status monitoring
- Notice and announcement distribution

## Architecture & Design Principles

- **Architecture:** Hexagonal Architecture / Clean Architecture
- **Design Patterns:** Domain Driven Design (DDD)
- **Principles:** SOLID Principles
- **Design Pattern:** MVC / MVVM
- **Key Concepts:** Inversion of Control (IoC), Dependency Injection (DI)

## Tech Stack

### Backend
- **Framework:** NestJS
- **Language:** TypeScript
- **Database:** PostgreSQL
- **ORM:** TypeORM / Prisma

### Frontend (Web)
- **Framework:** Next.js
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **State Management:** Zustand

### Mobile
- **Framework:** Flutter
- **State Management:** Bloc (intermediate) / GetX (easy)

### Cloud & DevOps
- **Cloud Platform:** Google Cloud Platform (GCP)
- **Container Orchestration:** Kubernetes
- **Local Development:** Skaffold
- **Package Management:** Helm
- **CI/CD:** GitHub Actions

## Team

| Role | Name | Responsibilities |
|------|------|------------------|
| 🚀 **DevOps & Infrastructure** | Ravi | GitHub, GCP, CI/CD, Kubernetes, Helm |
| 🎨 **Frontend Engineering** | Safrina | Next.js, React, Tailwind, Figma Wireframes |
| ⚙️ **Backend Engineering** | Ishakya | NestJS, TypeScript, API Design, Microservices |

### Team Responsibilities

#### Ravi - DevOps & Infrastructure
- Initialize GitHub repositories and branching strategy
- Setup Google Cloud Platform (GCP)
- CI/CD pipeline with GitHub Actions
- Kubernetes & Helm deployment

#### Safrina - Frontend Engineering
- Figma Wireframes (Web Dashboard & Mobile App)
- Next.js with TypeScript and Tailwind CSS
- Clean Architecture folder structure
- UI/UX implementation

#### Ishakya - Backend Engineering
- Bounded Contexts & Microservices design
- API Contracts with Swagger/OpenAPI
- NestJS with TypeScript
- Hexagonal Architecture (Ports & Adapters)

## Getting Started

### Prerequisites
- Node.js (v18+)
- Docker
- Kubernetes (minikube or GKE)
- Flutter SDK (for mobile)

### Clone the Repository
```bash
git clone https://github.com/Smart-Hostel-Platform/Smart-Hostel-and-Boarding-Management-Platform.git
cd Smart-Hostel-and-Boarding-Management-Platform
