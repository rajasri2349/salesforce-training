# Salesforce Summer Program – Day 3

## Difference Between App, Object, Record and Field

| Term | Meaning |
|------|----------|
| App | Collection of tabs and features used for a business process |
| Object | Database table that stores data |
| Record | Single row/data entry inside an object |
| Field | Individual data value inside a record |

---

## Standard vs Custom Objects

### Standard Objects
Objects already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

### Custom Objects
Objects created based on business needs.

Examples:
- Student
- Faculty
- Course
- Department

---

# College Management System Data Model

## Objects Created

- Student
- Faculty
- Course
- Department

---

## Relationships

| Object | Relationship |
|--------|---------------|
| Student → Course | Lookup Relationship |
| Faculty → Department | Lookup Relationship |
| Course → Department | Lookup Relationship |

---

## Data Model Diagram

(Add your screenshot/image here)

Example:

![Data Model](images/image1.png)

---

# Formula Fields

## 1. Full Name
Combines first name and last name automatically.

Why?
- Avoids manual typing mistakes.

---

## 2. Remaining Seats
Total Seats - Enrolled Students

Why?
- Shows available seats automatically.

---

## 3. Percentage
Marks Obtained / Total Marks * 100

Why?
- Automatic calculation saves time.

---

# Validation Rules

## 1. Email Cannot Be Empty

Prevents:
- Missing student contact details.

---

## 2. Student Age Cannot Be Negative

Prevents:
- Invalid age entries.

---

## 3. Course Seats Cannot Exceed Limit

Prevents:
- Overbooking students.

---

# Reflection

Companies need structured data because:
- Data becomes easy to search
- Relationships between records are maintained
- Reporting becomes easier
- Duplicate and inconsistent data is reduced
- Business processes become automated

Random Excel sheets become difficult to manage when data grows large.

---

# Reflective Questions

## 1. Why can’t companies manage everything using Excel sheets?

Excel sheets become difficult to maintain when data grows very large.

---

## 2. Why are relationships important between objects?

Relationships connect related business data together.

---

## 3. What problems happen if data is inconsistent?

Reports become incorrect and business decisions may fail.

---

## 4. Why should repetitive calculations be automated?

Automation saves time and reduces human errors.

---

## 5. Why should invalid data be blocked early?

It improves data quality and prevents future problems.

---

## 6. Why is Salesforce called a metadata-driven platform?

Because most functionality is configured without coding using metadata.
