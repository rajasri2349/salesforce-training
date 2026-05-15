# Salesforce Summer Program – Day 6

## Goal for Today

Today’s focus was understanding:
- SOQL basics
- Apex Triggers
- Event-driven systems
- Flow vs Trigger concepts
- Enterprise automation thinking

---

# What is SOQL?

SOQL (Salesforce Object Query Language) is used to retrieve data from Salesforce objects.

It helps developers:
- Find records
- Filter data
- Retrieve related information
- Work with databases inside Salesforce

Examples:
- Find all students in Course A
- Find attendance records
- Retrieve faculty details

---

# What is an Apex Trigger?

An Apex Trigger is code that runs automatically when data changes in Salesforce.

Triggers can execute:
- Before insert
- After insert
- Before update
- After update
- Before delete
- After delete

Triggers help automate business processes inside Salesforce.

---

# Difference: Flow vs Trigger

| Flow | Apex Trigger |
|------|---------------|
| Declarative (No code) | Programmatic (Code) |
| Easy to maintain | More powerful |
| Best for simple automation | Best for complex logic |
| Admin friendly | Developer focused |

---

# Difference: Before vs After Trigger

| Before Trigger | After Trigger |
|----------------|---------------|
| Runs before saving data | Runs after saving data |
| Used for validation/update | Used for related actions |
| Faster execution | Used for notifications/integrations |

---

# Trigger Use Cases

## 1. Student Registration
Event:
- After a student record is created

Action:
- Send welcome email automatically

---

## 2. Attendance Warning
Event:
- After attendance percentage updates

Action:
- Send warning if attendance is below 75%

---

## 3. Course Capacity Full
Event:
- After student enrollment

Action:
- Notify faculty that course is full

---

## 4. Fee Payment Completed
Event:
- After payment status changes to Paid

Action:
- Generate payment confirmation

---

## 5. Exam Result Published
Event:
- After exam marks are updated

Action:
- Notify students about results

---

# Flow vs Trigger Thinking

## Simple Email Notification
Use:
- Flow

Why:
- Easy automation without coding

---

## Complex Fee Eligibility Check
Use:
- Apex Trigger

Why:
- Requires complex business logic

---

## Updating Related Records
Use:
- Flow

Why:
- Easier for standard updates

---

## External API Integration
Use:
- Apex Trigger

Why:
- Better control and advanced handling

---

# Query Examples

- Find all students in Course A
- Find all courses handled by Faculty X
- Find students with attendance below 75%
- Find students who have not paid fees
- Find courses with maximum enrollments

---

# Reflection

Enterprise systems need event-driven behavior because actions must happen automatically when data changes.

Benefits:
- Faster response
- Reduced manual work
- Better accuracy
- Real-time automation
- Improved user experience

Without automation, systems become slow and inefficient.

---

# Reflective Questions

## 1. Why do systems need triggers?
Triggers automate actions and reduce manual effort.

---

## 2. Difference between polling and event-driven systems?

Polling:
- System continuously checks for changes

Event-driven:
- System reacts immediately after an event occurs

---

## 3. Why are database queries important?

Queries help retrieve the exact data needed efficiently.

---

## 4. When should Flows be preferred over Triggers?

Flows should be used for simple and standard automation.

---

## 5. What problems happen if automation logic becomes too complex?

- Difficult maintenance
- Performance issues
- Debugging problems

---

## 6. Why should developers think carefully before automating actions?

Poor automation can create incorrect data updates and system issues.

---

# Light Completion Sprint

## Modules Completed

1. Search Solution Basics
2. Agentforce 360 Platform Events Basics
3. Command-Line Interface

---

# One Learning From Each Module

## Search Solution Basics
Search helps users quickly find records and improves productivity.

---

## Agentforce 360 Platform Events Basics
Platform events allow systems to communicate automatically using event-driven architecture.

---

## Command-Line Interface
CLI tools help developers work faster and automate tasks efficiently.

---

# One Doubt / Question

How are platform events used in real-world enterprise systems?

---

# Platform Event Thinking

Example:
When a student completes registration:
- Faculty gets notified
- Fee system updates automatically
- Student receives confirmation email

This allows multiple systems to react instantly.

---

# CLI Reflection

Developers prefer command-line tools because they are faster and help automate repetitive tasks.

CLI also improves productivity for large projects.

---

# Search Reflection

Fast and accurate search is important because enterprise systems contain huge amounts of data.

Good search improves efficiency and saves time.

---

# Overall Learning

Today I learned:
- Basics of SOQL
- Apex Trigger concepts
- Event-driven systems
- Salesforce CLI basics
- Enterprise search systems
- Flow vs Trigger differences

---

# Screenshots

Add:
- Trailhead completion screenshots
- Module screenshots
- Progress screenshots
