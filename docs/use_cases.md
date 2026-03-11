# Brief Use Cases

Date: March 11, 2026

## UC-01 Add Plane to Fleet

- Primary Actor: Airline Administrator
- Goal: add a plane record to the system.
- Brief Description: the administrator enters plane information and the system stores it for future flight scheduling.

## UC-02 Define Flight Class Configuration

- Primary Actor: Airline Administrator
- Goal: define which flight classes are available and how many seats each class has.
- Brief Description: the administrator configures class capacity information that will later be used when scheduling flights and booking reservations.

## UC-03 Schedule Flight

- Primary Actor: Airline Administrator
- Goal: create a scheduled flight.
- Brief Description: the administrator selects route and schedule information, assigns a plane, and makes the flight available for customer queries.

## UC-04 Query Flights

- Primary Actor: Customer
- Goal: find flights that match travel needs.
- Brief Description: the customer searches by origin, destination, date, and class, and the system returns matching flights with availability.

## UC-05 Book Reservation

- Primary Actor: Customer
- Goal: reserve a seat on a selected flight.
- Brief Description: the customer chooses a flight and class, submits reservation details, and the system creates an unconfirmed reservation if seats are available.

## UC-06 Confirm Reservation

- Primary Actor: Customer
- Goal: confirm a reservation after payment.
- Brief Description: the customer completes payment confirmation and the system changes the reservation status from unconfirmed to confirmed.

## UC-07 Cancel Reservation

- Primary Actor: Customer
- Goal: cancel an existing reservation.
- Brief Description: the customer requests cancellation, the system checks refund rules, updates the reservation status, and returns the refund result.

## UC-08 Reallocate Unconfirmed Reservation

- Primary Actor: Airline Administrator
- Goal: free scarce seat inventory.
- Brief Description: when seats are scarce, the administrator triggers a manual reallocation and the system removes the oldest unconfirmed reservation from the affected seat inventory.