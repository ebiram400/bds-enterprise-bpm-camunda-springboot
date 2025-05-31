# 🏢 BDS Enterprise BPM Platform

This repository contains a real-world **Business Process Management (BPM)** platform built with **Camunda**, **Spring Boot**, and **Java 17+**.

It simulates the operations of a fictional company — **BDS (Business Digital Solutions)** — that automates and manages complex workflows for multiple domains:
- Banking
- Legal and Media Rights
- Energy Grid Management
- Telecom and Fiber Optic Providers

## 🌐 Purpose

The project is designed as a **portfolio-grade**, **enterprise-level demonstration** of:
- BPMN modeling
- Task coordination
- Domain separation
- Scalable and clean backend architecture
- Integration of real-life workflows used in German and European companies

It's ideal for showcasing my ability to work with **complex business logic**, especially for positions in **Germany** where BPM tools like Camunda are common.

## 🧱 Architecture

- Java 17+
- Spring Boot 3.x
- Camunda Platform 7/8 (depending on version branch)
- RESTful APIs (with OpenAPI / Swagger)
- Modular domain layers
- Database: PostgreSQL
- Docker (optional for deployment)

## 📁 Domain Modules

| Domain    | Key Processes |
|-----------|----------------|
| **Banking** | Customer onboarding, Loan approval, Complaint handling |
| **Legal**   | Royalty invoices, Rights distribution |
| **Energy**  | Grid maintenance, Outage response, Service ordering |
| **Telecom** | Customer onboarding, Billing, Fiber optic service requests |

Each domain has:
- BPMN processes (`/resources/bpmn/<domain>/`)
- Java packages for services and controllers (`/java/com/bds/<domain>/`)
- Test cases for process simulation

## ⚙️ How to Run

git clone https://github.com/ebiram400/bds-enterprise-bpm-camunda-springboot.git
cd bds-enterprise-bpm-camunda-springboot
./mvnw spring-boot:run
Visit Camunda Cockpit at http://localhost:8080

Interact with APIs via Swagger UI or Postman

🔐 Roles
Manager: Oversees processes, assigns tasks

Clerk: Handles manual service tasks

Customer: Submits service or legal requests

📫 Author
Ebrahim Rahimi
Backend & BPM Developer | Based in Mashhad, Iran
Seeking full-time employment in Germany (visa support required)
📧 ebiram400@gmail.com
🔗 GitHub Profile
