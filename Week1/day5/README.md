# Salesforce Summer Program - Day 5

## What is Apex?

Apex is a programming language developed by Salesforce that allows developers to add custom business logic to Salesforce applications.

It is used when Flows and configuration are not enough for complex business requirements.

---

## Topics Learned
- Apex basics
- Variables and classes
- Conditional statements
- Loops
- DML operations
- SOQL basics
- Business logic in Salesforce

---

## Flow vs Apex

| Flow | Apex |
|------|------|
| No-code automation | Programming-based automation |
| Easy to build | Requires coding knowledge |
| Best for simple processes | Best for complex logic |
| Faster development | More flexible and powerful |

---

## Configuration vs Coding

### Configuration
- Uses clicks instead of code
- Faster for simple automation
- Example: Validation Rules, Flows

### Coding
- Uses Apex programming
- Handles advanced business logic
- Example: Payment integrations, complex calculations

---

## Real Examples Where Apex Is Needed

1. Complex fee calculation system
2. Integration with external payment gateway
3. Advanced student eligibility verification

### Why Apex is Needed
Flows may not handle highly complex logic, integrations, or large-scale processing efficiently.

---

## Integrated College Management System

### CRM
Manages student admissions and communication.

### Objects
- Student
- Course
- Faculty

### Relationships
- Student ↔ Course
- Faculty ↔ Course

### Validation
Email field must not be empty.

### Flow
Send automatic notifications when seats are full.

### Apex
Custom eligibility and fee calculation logic.

---

## Pseudocode Examples

### Example 1
IF seats are full  
THEN block registration

### Example 2
IF attendance < 75%  
THEN notify student

---

## Reflection

Enterprise systems need programming because some business requirements are too complex for simple configuration tools. Apex provides flexibility, customization, and integration capabilities for advanced business logic.
