# StageFlow

StageFlow is a backend-heavy workflow management platform designed to demonstrate a clean, maintainable, and scalable architecture using **Spring Boot** and **Java 21**.

The project is intentionally structured following **Clean Architecture principles**, with a strong separation of concerns between business logic, application use cases, technical infrastructure, and delivery mechanisms (REST API).

This repository is built as a **senior-level reference project**, focusing on:
- Architecture clarity
- Long-term maintainability
- Testability
- Production-ready mindset

---

## 🎯 Architectural Goals

- Enforce a **clear separation of responsibilities**
- Keep the **business domain independent** from frameworks and technical details
- Allow the application to evolve without tight coupling
- Make architectural decisions **explicit and readable**

The architecture is organized around four main layers:

- **Domain**: core business logic and rules
- **Application**: use cases and orchestration
- **Infrastructure**: technical implementations (database, security, external systems)
- **API**: REST controllers and HTTP-level concerns

All dependencies flow **inward**, toward the domain layer.