# GitHub README – Task Manager API

## Overview

The **Task Manager API** is a backend system built to manage tasks in a clean, secure, and scalable way. It focuses on **real-world backend architecture**, including authentication, authorization, and relational data modeling.

This project was built to simulate how professional task-based systems (like Jira or Asana) are structured on the server side.

---

## What This Project Does

* Allows users to create, read, update, and delete tasks
* Groups tasks under projects for better organization
* Protects all actions using authentication and permissions
* Ensures data consistency using a relational database

---

## Key Features

* **JWT Authentication** – only logged-in users can access protected routes
* **Permission-Based Authorization** – users can only perform allowed actions
* **Project-Based Task Organization** – tasks belong to projects
* **Clean Modular Architecture** – separated controllers, services, DTOs, and entities
* **Data Validation & Error Handling** – prevents invalid or unsafe operations

---

## Tech Stack

* NestJS
* TypeScript
* MySQL
* TypeORM
* REST APIs

---

## Architecture Overview

* **Controllers** handle incoming HTTP requests
* **Services** contain business logic
* **DTOs** validate incoming data
* **Entities** represent database tables

This structure mirrors production-ready backend systems.

---

## What I Learned

* How to structure backend applications cleanly
* How authentication and authorization work together
* How to model relational data safely
* How to debug and solve backend issues using documentation and tooling

---

## Why This Project Matters

This project demonstrates strong backend fundamentals and the ability to design systems that are secure, maintainable, and scalable.

---

# GitHub README – MIDAS (Distributed Financial Ledger)

## Overview

**MIDAS** is a distributed backend system designed to process financial transactions in real time. It listens to transaction events, validates them against a database, communicates with an external incentive service, and exposes a public API for balance queries.

This project was completed as part of a **virtual internship** and focuses on understanding **event-driven systems and service communication**.

---

## What This Project Does

* Consumes transaction events from a message broker
* Validates user balances before processing transfers
* Records transactions in a database
* Communicates with an external service to apply incentives
* Exposes a REST API for querying balances

---

## System Flow (High Level)

1. Transaction event is received
2. Sender balance is validated
3. Database is updated
4. Incentive service is called
5. Bonus is applied to recipient

---

## Tech Stack (Project Exposure)

* Spring Boot
* Apache Kafka
* JPA
* H2 Database
* REST APIs

> Note: Technologies listed here reflect **project exposure during a structured internship**, not daily standalone usage.

---

## Key Challenges & Solutions

* **Asynchronous processing** – learned how event-driven systems behave
* **JSON deserialization issues** – solved via explicit configuration
* **Service connectivity problems** – fixed through proper port configuration
* **Optional type handling** – safely managed missing database records

---

## What I Learned

* How event-driven systems work in practice
* How financial data integrity is maintained
* How multiple backend services communicate
* How to debug real-world backend issues

---

## Why This Project Matters

MIDAS demonstrates experience with distributed systems, financial logic, and real production-style backend challenges.


