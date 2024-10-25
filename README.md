# DevOps Adventure Baseline 🚗

### A Vehicle Dealership Application

---

## Overview

**DevOps Adventure Baseline** is a vehicle dealership management project created in Python with PostgreSQL as the primary database solution. This application serves as a robust platform to manage vehicle inventories, sales, customer information, and business operations within a dealership environment. With a focus on scalability, maintainability, and efficiency, this project showcases our team’s journey in implementing a cohesive backend solution that addresses the needs of modern dealerships.

## Project Objectives

The core objectives of this project are:

- **Develop** a scalable, backend solution for managing a vehicle dealership.
- **Utilize** Python and PostgreSQL as the primary technology stack.
- **Incorporate** DevOps best practices to streamline development and deployment.
- **Implement** API endpoints to manage all dealership functionalities.
- **Ensure** data consistency, security, and integrity within the PostgreSQL database.

---

## Project Planning and Setup

Our approach to building the **DevOps Adventure Baseline** application began with a thorough planning phase to ensure clarity on objectives, team roles, and project scope.

1. **Team Role Assignment**:
   - Each member of the team was assigned specific roles based on their strengths and expertise.
   - Team members include:
     - **Gonçalo Batista** – Database Architect & Backend Developer
     - **Nuno Machado** – API Specialist & System Integrator
     - **Henrique Prata** – DevOps Engineer & Project Coordinator

2. **Requirement Gathering**:
   - We performed detailed requirement gathering and analysis to define the dealership’s business rules and critical functionalities.
   - Key requirements included managing vehicle data, user authentication, and sales records.

3. **Repository and Branch Setup**:
   - We initiated the project by creating a Git repository and defining baseline branches:
     - **Main branch**: Primary branch with stable releases.
     - **Development branch**: Branch for active feature development.
   - This structure ensured an organized workflow and minimized integration issues.

---

## Development Process

### Tools & Frameworks

- **Primary Language**: Python
- **Database**: PostgreSQL
- **Web Framework**: FastAPI – selected for its asynchronous capabilities and ease of use.
- **Dependency Management**: Poetry – streamlined our dependency management and versioning.

### Key Development Milestones

1. **API and Endpoint Development**:
   - Created API endpoints using **FastAPI** for user authentication, vehicle inventory management, and dealership operations.
   - Ensured that each endpoint follows RESTful principles to maintain a clean and standardized API structure.

2. **Database Design and Implementation**:
   - Designed the PostgreSQL database schema to accommodate vehicle data, user data, and transactional information.
   - Created tables, defined relationships, and ensured data integrity to meet the dealership's operational needs.

3. **Dependency Management**:
   - Managed project dependencies with **Poetry** to simplify package installation and maintain version consistency.
   - Integrated FastAPI and other essential libraries efficiently through Poetry’s streamlined workflow.

4. **Continuous Integration and Continuous Deployment (CI/CD)**:
   - Configured CI/CD pipelines to automate testing, build, and deployment.
   - Set up tests for API endpoints and database interactions to ensure reliability and performance.

---

## Project Structure

```plaintext
devops-adventure-baseline/
├── app/
│   ├── main.py                # Main application entry point
│   ├── api/                   # API route definitions
│   ├── models/                # Database models
│   ├── schemas/               # Data schemas for API endpoints
│   ├── config.py              # Configuration settings
├── database/
│   ├── migrations/            # Database migration files
│   ├── db_init.sql            # Initial database setup script
├── tests/
│   ├── test_endpoints.py      # Unit tests for API endpoints
│   ├── test_db.py             # Unit tests for database operations
├── .gitignore
├── README.md
├── pyproject.toml             # Poetry dependency management file
└── requirements.txt           # Project dependencies
