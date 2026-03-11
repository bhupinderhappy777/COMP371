# COMP 371 Airline Reservation System

This repository contains the Winter 2026 group project for COMP 371 (Object Oriented Modeling and Design).
The goal is to design and implement an airline reservation system by following the Unified Process and applying UML-driven object-oriented design.

## Overview

The system supports two major service groups:

1. Provisioning services for the airline:
- Add planes to the fleet
- Define flight classes
- Schedule flights

2. Customer-facing services:
- Query flights using conditions (origin, destination, date, class)
- Book reservations
- Confirm reservations after payment
- Cancel reservations and process refunds

## Ticket and Refund Rules

| Ticket Type | Fare Percentage | Refundability |
| --- | --- | --- |
| First Class | 100% | Full refund on cancellation |
| Coach | 85% | Full refund on cancellation |
| Economy | 70% | Full refund only when canceled at least 14 days before departure |

Additional reservation rule:
- A reservation is considered confirmed only after payment.
- Unconfirmed reservations may be reallocated when seats become scarce.

## Project Deliverables

The project deliverables:

1. Use cases, use case diagram, and complementary requirement documents
2. Domain model diagram
3. UML interaction diagrams (SSD/sequence/activity)
4. Operation contracts
5. Design class diagram (DCD) with applied patterns
6. Java implementation (UI + persistence + business logic)
7. Implementation report with workflow explanation and labeled screenshots

## Planned Tech Stack

- Language: Java
- UI: Swing
- Persistence: File-based storage
- Design Approach: Layered architecture (UI, application services, domain, persistence)

## Planned Repository Layout

```text
COMP371/
	README.md
	docs/        # use cases, specs, contracts, report draft
	diagrams/    # UML and design artifacts
	src/         # Java source code
	data/        # persisted files and seed data
```

## Current Status

Planning and requirements phase.

## Team

- Member 1: Bhupinder Singh Gill
- Member 2: Navpreet Singh
- Member 3: Prabhjeet Kaur

## Team Responsibilities

- Prabhjeet Kaur: Use cases, use case diagram, and complementary requirement documents.
- Bhupinder Singh Gill: Diagrams and code implementation.
- Navpreet Singh: Assist with code implementation and later testing with screenshots to ensure everything is working fine.

