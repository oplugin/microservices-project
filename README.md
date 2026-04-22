# Microservices Project — Contracts / Suppliers / Orders

## Overview
Проект демонстрирует архитектуру из трёх микросервисов:
- **Contracts Service**
- **Suppliers Service**
- **Orders Service**

Каждый сервис:
- Spring Boot
- PostgreSQL / MongoDB
- Kafka (events)
- Docker Compose
- REST API (OpenAPI/Swagger)

## Architecture
- Event-driven взаимодействие через Kafka
- API Gateway для маршрутизации
- Отдельные БД на сервис
- Idempotency, retry, DLQ

## Services
- contracts-service — управление контрактами
- suppliers-service — онбординг и управление поставщиками
- orders-service — создание и обработка заказов

## Run locally

## Documentation
- `/docs/architecture` — диаграммы
- `/docs/api` — OpenAPI спецификации
- `/docs/events` — события Kafka

## Tech Stack
Java 17, Spring Boot 3, Kafka, PostgreSQL, MongoDB, Docker, Testcontainers
