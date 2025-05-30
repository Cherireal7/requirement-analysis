# Requirement Analysis in Software Development

## Introduction
This repository contains the Requirement Analysis phase of a simulated software development project — a **Booking Management System**. It outlines key activities, types of requirements, use case diagrams, and acceptance criteria following SDLC best practices. The goal is to document and model clear, precise, and actionable requirements that align with real-world industry standards.

---

## What is Requirement Analysis?

Requirement Analysis is a process in the Software Development Life Cycle (SDLC) where developers, stakeholders, and analysts identify, document, and analyze the functional and non-functional needs of a system. It lays the groundwork for the project’s success by ensuring that all requirements are well understood and agreed upon before development begins.

This phase bridges the gap between a client’s needs and the technical solution by:
- Collecting user expectations and business goals
- Defining system boundaries and interactions
- Preventing scope creep and misunderstandings during development

---

## Why is Requirement Analysis Important?

1. **Clarity and Alignment**  
   It helps all stakeholders maintain a shared understanding of project goals and expectations.

2. **Reduces Development Risks**  
   By identifying potential issues early, it minimizes rework and project delays.

3. **Improves Product Quality**  
   Clearly defined requirements ensure the product meets both user and business needs effectively.

---

## Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collect data from stakeholders through interviews, surveys, and observation.

- **Requirement Elicitation**  
  Explore and clarify ambiguous or conflicting requirements using prototypes or user stories.

- **Requirement Documentation**  
  Record requirements clearly in structured formats (e.g., user stories, requirement specs).

- **Requirement Analysis and Modeling**  
  Analyze feasibility and model the system through diagrams or specifications.

- **Requirement Validation**  
  Review requirements with stakeholders to confirm accuracy, completeness, and alignment with goals.

---

## Types of Requirements

### Functional Requirements

These define what the system **should do**.

**Examples:**
- Users can sign up and log in to their account.
- Admin can add or remove available rooms.
- Users can make, view, or cancel a booking.
- The system sends confirmation emails upon booking.

### Non-functional Requirements

These define **how** the system performs its functions.

**Examples:**
- The booking system must respond within 2 seconds under average load.
- The application must support at least 10,000 users concurrently.
- Data must be encrypted and comply with GDPR standards.
- The UI should be mobile responsive and accessible (WCAG 2.1).

---

## Use Case Diagrams

Use Case Diagrams provide a visual overview of system actors and their interactions. They help communicate functionality at a glance and guide developers and stakeholders through user behavior expectations.

![Use Case Diagram](alx-booking-uc.png)

---

## Acceptance Criteria

Acceptance Criteria are the predefined conditions that must be met for a feature to be considered complete and accepted by the client or end-user.

They:
- Ensure all parties agree on the definition of “done”
- Help QA teams design test cases
- Reduce ambiguity during development

**Example: Checkout Feature – Acceptance Criteria**
- ✅ The user must be logged in to proceed to checkout.
- ✅ The system must display a booking summary with cost breakdown.
- ✅ Payment should be processed securely via integrated payment gateway.
- ✅ A confirmation email must be sent upon successful payment.
- ✅ The user should be redirected to a “Booking Success” page with reference ID.

---

## Author
Cherinet Demeke – ALX Software Engineering Student  
#ALX_SE #ALX_FE @alx_africa

