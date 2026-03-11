# Vision

Date: March 11, 2026

## Purpose

This document captures the Phase 1 vision for the COMP 371 Airline Reservation System.

## Problem Statement

The project needs a small airline reservation system that supports basic airline setup and customer reservation services. The system must allow the airline to manage flight offerings and allow customers to search, book, confirm, and cancel reservations while following the given fare and refund rules.

## Stakeholders and Users

- Airline Administrator: manages planes, flight classes, flight schedules, and reservation reallocation decisions.
- Customer: searches flights, books reservations, confirms payment, and cancels reservations.
- Project Team: produces the required UML artifacts, implementation, and report.

## Business Goals

- Provide a working reservation system that satisfies the project requirements.
- Airline administrators can easily manage flight offerings and inventory.
- Customers can easily find and manage their reservations.
- The system correctly applies the defined refund and confirmation rules.

## High-Level System Capabilities

- Add planes to the fleet.
- Define available ticket classes for flights.
- Schedule flights.
- Query flights by origin, destination, date, and ticket class.
- Book reservations.
- Confirm reservations after payment.
- Cancel reservations and process refunds according to policy.
- Reallocate unconfirmed reservations manually when seats become scarce.

## Scope for Release 1

Included:
- Provisioning services for airline administration.
- Core customer reservation services.
- Refund and confirmation rules defined in the project brief.
- File-based persistence using JSON.

Excluded:
- Multi-leg itineraries.
- Dynamic pricing.
- Loyalty programs.
- External payment gateway integration.
- Advanced authentication.

## Success Criteria

- The system supports the required main flows from flight setup to reservation cancellation.
- The analysis and design artifacts stay consistent with the implementation.
- The implementation is functional and demonstrates the end-to-end workflow.