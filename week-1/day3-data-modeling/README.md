# Day 3 - Data Modeling

# 1. Difference Between App, Object, Record, and Field

## App
An App is a collection of tools and objects for a business process.

Example:
College Management App

---

## Object
An Object stores related data.

Examples:
- Student
- Course
- Faculty

---

## Record
A Record is a single entry inside an object.

Example:
Student Name = Rahul

---

## Field
A Field stores one piece of information.

Examples:
- Name
- Age
- Email

---

# 2. Standard vs Custom Objects

## Standard Objects
Objects already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

---

## Custom Objects
Objects created by users based on business needs.

Examples:
- Student
- Faculty
- Department

---

# 3. College Data Model

## Objects
- Student
- Faculty
- Course
- Department

---

## Relationships

### Department → Course
One department can have many courses.

### Faculty → Course
One faculty can teach many courses.

### Student → Course
Many students can enroll in courses.

---

## Relationship Type
Lookup Relationships are used between objects.

---

# Simple Diagram

Department
   |
   ---> Course
            |
            ---> Faculty
            |
            ---> Student

---

# 4. Formula Fields

## Full Name
Combines first name and last name automatically.

Reduces manual work and mistakes.

---

## Percentage
Calculates student percentage automatically.

No need to calculate manually every time.

---

## Remaining Seats
Calculates available seats in a course.

Helps manage admissions easily.

---

# 5. Validation Rules

## Email Cannot Be Empty

Prevents missing student contact details.

---

## Student Age Cannot Be Negative

Prevents invalid age data.

---

## Course Seats Cannot Exceed Limit

Prevents overbooking of students.

---

# 6. Reflection

## Why Structured Data Matters

Companies need structured data because random spreadsheets are hard to manage.

Structured data helps:
- Store information properly
- Avoid duplicate data
- Build relationships between records
- Generate reports easily
- Improve business efficiency

---

# Reflective Questions

## 1. Why can’t companies use Excel sheets for everything?

Excel becomes difficult when data grows large and many users work together.

---

## 2. Why are relationships important?

Relationships connect related data and make systems organized.

---

## 3. What happens if data is inconsistent?

It causes errors, confusion, and wrong business decisions.

---

## 4. Why automate calculations?

Automation saves time and reduces mistakes.

---

## 5. Why block invalid data early?

It improves data quality and system reliability.

---

## 6. Why is Salesforce metadata-driven?

Because Salesforce allows customization without changing core software code.

---
