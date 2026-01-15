# AutoFlow

AutoFlow is a distributed, event-driven workflow orchestration platform inspired by tools like Temporal, Zapier, and Airflow.

## Tech Stack
- Java 17, Spring Boot
- Apache Kafka
- Redis
- PostgreSQL
- Docker, AWS (planned)

## High-Level Architecture
- Orchestrator Service: Manages workflow definitions and scheduling
- Worker Service: Executes tasks asynchronously
- Kafka: Event-driven communication
- Redis: Execution state & idempotency
- PostgreSQL: Workflow metadata persistence

## Status
🚧 Actively under development. Initial orchestration and execution flow in progress.