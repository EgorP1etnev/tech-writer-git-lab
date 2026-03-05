# System Architecture

The Data Monitoring Platform is built using a microservice architecture.

The platform collects metrics from communication towers and stores them
in a centralized database. Services communicate via REST APIs.

The main components include:

- API Gateway
- Metrics Service
- Authentication Service
- PostgreSQL Database