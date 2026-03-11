# Actors and Use-Case Model

Date: March 11, 2026

## Actors

- Customer
  - Goal: find flights, make reservations, confirm payment, and cancel reservations.

- Airline Administrator
  - Goal: maintain the flight offering and manage reservation reallocation decisions.

## Use-Case List

| ID | Use Case | Primary Actor | Goal |
| --- | --- | --- | --- |
| UC-01 | Add Plane to Fleet | Airline Administrator | Register a plane for use in the system. |
| UC-02 | Define Flight Class Configuration | Airline Administrator | Define available ticket classes and capacities. |
| UC-03 | Schedule Flight | Airline Administrator | Create a scheduled flight using existing fleet and class data. |
| UC-04 | Query Flights | Customer | Search for flights that match travel conditions. |
| UC-05 | Book Reservation | Customer | Reserve a seat in a selected flight class. |
| UC-06 | Confirm Reservation | Customer | Confirm a reservation after payment. |
| UC-07 | Cancel Reservation | Customer | Cancel a reservation and receive any eligible refund. |
| UC-08 | Reallocate Unconfirmed Reservation | Airline Administrator | Reassign scarce seat inventory by removing the oldest unconfirmed reservation first. |

## Architecturally Significant Use Cases

The following use cases are most important for later analysis and design:

- UC-03 Schedule Flight
- UC-05 Book Reservation
- UC-06 Confirm Reservation
- UC-07 Cancel Reservation

## Notes for Phase 1

- The use cases in this phase are intentionally brief.
- Detailed SSDs, operation contracts, and design diagrams belong to later phases.
- This artifact is used to define scope and actor goals before deeper analysis begins.