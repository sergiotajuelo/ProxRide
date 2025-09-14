# ProxRide (Ride-Sharing Backend)

ProxRide is a **backend system for a ride-sharing platform** designed to demonstrate **clean software architecture, SOLID principles, and common design patterns**. 

The project will evolve in multiple stages: starting with a minimal backend MVP and gradually extending to include persistence, APIs, notifications, distributed messaging, and cloud deployment.  

---

## 📌 Project Goals
- Showcase **clean, modular, and maintainable code** using SOLID principles.
- Apply **design patterns** (Strategy, Observer, etc) in real-world use cases.
- Build a **REST API** for passengers and drivers to request and manage rides.
- Implement a **ride-matching algorithm** to assign the nearest available driver.
- Add support for multiple **fare calculation strategies** (Standard, Shared, Luxury).
- Persist data with **PostgreSQL** and manage schema migrations.
- Provide **automated testing** (unit, integration).
- Extend with **Kafka for event-driven architecture**.
- Deploy the system to **AWS** with CI/CD pipelines.

---

## 🛠 Tech Stack
- **Language:** Java 17
- **Framework:** Spring Boot
- **Database:** PostgreSQL (via Spring Data JPA)
- **Messaging (planned):** Apache Kafka
- **Testing:** JUnit 5, Mockito
- **Docs:** OpenAPI

---

## 🚀 Roadmap (Milestones)
- **v0.1 - MVP:** Core domain, ride-matching algorithm, fare strategies.
- **v0.2 - API & Persistence:** REST endpoints + PostgreSQL + migrations.
- **v0.3 - Notifications:** Observer pattern for ride status updates.
- **v0.4 - CI & Docker:** Dockerized app + GitHub Actions.
- **v1.0 - Release:** Deploy to AWS + documentation + demo.

Future evolutions: Kafka events, microservices split.
