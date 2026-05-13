# Day 5 - Apex Introduction

# 1. What is Apex?

Apex is a programming language used in Salesforce to build custom business logic and automation.

It helps developers create advanced features that cannot be done using only clicks or flows.

---

# 2. Difference Between Flow and Apex

## Flow

- No-code automation
- Easy to build
- Used for simple business processes

Examples:
- Sending emails
- Updating records automatically

---

## Apex

- Programming-based automation
- Used for advanced logic
- More flexible and powerful

Examples:
- Complex calculations
- External integrations

---

# 3. Difference Between Configuration and Coding

## Configuration

Customization using clicks without writing code.

Examples:
- Validation Rules
- Flows
- Formula Fields

---

## Coding

Customization using Apex programming.

Examples:
- Complex automation
- Custom business logic
- API integrations

---

# 4. Real Examples Where Apex Is Needed

## 1. Complex Fee Calculation

Different fee calculations based on scholarships and attendance.

### Why Apex?
Logic becomes too complex for Flow.

---

## 2. External Payment Integration

Connecting Salesforce with payment gateways.

### Why Apex?
Requires API communication and custom logic.

---

## 3. Advanced Student Eligibility Check

Checking marks, attendance, and special conditions together.

### Why Apex?
Needs complex conditions and calculations.

---

# 5. Integrated College Management System

## CRM
Used to manage student admission and records.

---

## Objects
- Student
- Faculty
- Course
- Department

---

## Relationships
- Students are connected to Courses
- Courses belong to Departments
- Faculty teaches Courses

---

## Validation Rules
- Email cannot be empty
- Age cannot be negative

---

## Formula Fields
- Remaining Seats
- Percentage Calculation

---

## Flow
Automatically sends confirmation email after registration.

---

## Apex
Handles advanced eligibility and fee calculation logic.

---

# 6. Pseudocode Examples

## Example 1

IF seats are full  
THEN block registration

---

## Example 2

IF attendance < 75%  
THEN notify student

---

## Example 3

IF fee is unpaid  
THEN block exam registration

---

# 7. Reflection

## Why Enterprise Systems Need Programming

Enterprise systems have complex business requirements that cannot always be handled using only clicks and configuration. Programming provides flexibility, advanced automation, integrations, and custom logic needed for large real-world systems.

---

# Reflective Questions

## 1. Why is Apex needed if Salesforce already has Flows?

Because some business logic is too complex for Flow.

---

## 2. When should developers prefer no-code solutions?

For simple automation and faster development.

---

## 3. What problems require custom programming?

Complex calculations, integrations, and advanced automation.

---

## 4. Why is business logic important?

It helps systems follow company rules correctly.

---

## 5. Why avoid unnecessary coding?

Too much coding increases complexity and maintenance.

---

## 6. How does programming increase flexibility?

It allows developers to build custom solutions for business needs.

---
