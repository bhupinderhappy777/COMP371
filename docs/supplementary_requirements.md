# Supplementary Requirements

Date: March 11, 2026

## Purpose

This document captures simple supporting requirements and business rules that do not need to be fully described inside the brief use cases.

## Functional Rules

- A reservation becomes confirmed only after payment confirmation.
- First Class tickets are charged at 100% of the base fare.
- Coach tickets are charged at 85% of the base fare.
- Economy tickets are charged at 70% of the base fare.
- First Class cancellations receive a full refund.
- Coach cancellations receive a full refund.
- Economy cancellations receive a full refund only when cancelled at least 14 days before departure.
- Unconfirmed reservations may be reallocated manually by the airline administrator when seats are scarce.
- When reallocation is needed, the oldest unconfirmed reservation is the first candidate to lose its seat.

## Non-Functional Requirements

- The system will be implemented in Java.
- The user interface will be built with Swing.
- The application will use JSON files for persistence.
- The first release should remain simple and easy to demonstrate.
- The system should support a clean end-to-end workflow for screenshots and report evidence.

## Constraints

- No external payment gateway will be integrated.
- No advanced authentication or role management is required.
- Seat handling will be based on seat counts per class rather than individual seat objects.

## Query Requirements

- Customers can query flights by origin.
- Customers can query flights by destination.
- Customers can query flights by date.
- Customers can query flights by ticket class.

## Open Items for Later Phases

- Final domain model details.
- Operation contracts.
- Design class diagram with patterns.
- UI layout details.