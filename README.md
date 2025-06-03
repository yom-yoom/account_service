# 📦 Account Service

## 📄 Описание

Микросервис отвечает за управление аккаунтами пользователей в системе. Он позволяет создавать различные типы аккаунтов и счетов, управлять тарифами некоторых типов аккаунтов, а также управлять их балансом.

## ⚙️ Технологии

### Основа:

- Java 17
- Spring Boot 3.0.6

### Базы:

- PostgreSQL
- Redis
- Liquibase

### Общение микросервисов:

- Kafka
- OpenFeign

### Тестирование:

- JUnit 5
- Mockito
- AssertJ
- Testcontainers

### Прочее:

- Lombok
- MapStruct
- Springdoc OpenAPI
- CI Pipeline (GitHub Actions)
- JaCoCo
- Slf4j
- Docker
- WebClient

## 🔗 Связанные сервисы

- User Service - для связи с аккаунтов с пользователями
- Payment Service - для связи с платежами
