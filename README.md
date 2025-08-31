# Requirement Analysis in Software Development

This repository documents the Requirement Analysis phase of a software development lifecycle (SDLC) project.  
It is based on a Booking Management System case study and shows how requirements are gathered, structured, and visualized before development.

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, documenting, and managing the needs of stakeholders for a software system.  
It defines what the system should do, reduces misunderstandings, and serves as the foundation for design, implementation, and testing.

## Why is Requirement Analysis Important?

1. Prevents costly mistakes by catching errors early.  
2. Provides clarity and alignment among stakeholders.  
3. Guides developers, testers, and designers with a clear blueprint.  

## Key Activities in Requirement Analysis

- **Requirement Gathering** – collecting raw requirements from stakeholders.  
- **Requirement Elicitation** – clarifying and refining what users really need.  
- **Requirement Documentation** – writing structured requirement documents.  
- **Requirement Analysis and Modeling** – using diagrams and models for understanding.  
- **Requirement Validation** – checking correctness and consistency of requirements.  

## Types of Requirements

### Functional Requirements
Define what the system must do. Examples for the Booking Management System:
- Users can search available rooms by date and type.  
- Users can book a room online.  
- Admins can add, edit, or remove rooms.  
- System sends confirmation email after booking.  

### Non-functional Requirements
Define how the system performs. Examples:
- Support at least 500 users at the same time.  
- Booking page loads within 3 seconds.  
- Payment details are encrypted for security.  
- System uptime of 99.9% annually.  

## Use Case Diagrams

Use case diagrams show how users interact with the system.  
Actors for the booking system include the **Customer** and the **Admin**.  

Planned use cases: Search Room, Book Room, Checkout, Manage Rooms, View Bookings.  

![Booking System Use Case Diagram](./alx-booking-uc.png)

## Acceptance Criteria

Acceptance criteria set the conditions for a feature to be considered complete.  

Example for the Checkout feature:  
- Given a customer has selected a room and goes to checkout,  
- When they provide valid payment details,  
- Then the system processes the payment, confirms the booking, and sends an email within 1 minute.  

## Repository Structure

