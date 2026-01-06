# payslip-infra

This repository contains the infrastructure, documentation, and system-level configuration for the Payslip Platform. It acts as the central reference point for how the entire system is structured, developed, and deployed.

The platform follows a decoupled architecture with a Django backend responsible for business logic, authentication, and data persistence, and a Next.js frontend responsible for user experience and presentation. All services communicate strictly over well-defined APIs.

This repository does not contain application code. Instead, it documents architectural decisions, local development setup, environment configuration, and deployment workflows. It also serves as the onboarding guide for developers and the single source of truth for how the platform operates across environments.

Related Repositories

Backend: Django REST API handling authentication, payroll logic, and data access.
Frontend: Next.js application providing the web interface for admins and employees.

Together, these repositories form a scalable, production-ready foundation designed to support multiple clients, environments, and future growth without requiring architectural changes.
