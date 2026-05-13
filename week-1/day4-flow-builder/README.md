# Day 4 - Flow Builder

# 1. What is Flow Builder?

Flow Builder is a Salesforce automation tool used to automate business processes without coding.

It helps companies:
- Reduce manual work
- Save time
- Improve accuracy
- Automate repetitive tasks

---

# 2. Types of Flows

## Screen Flow

Screen Flow interacts with users through screens and collects information from them.

Example:
Student admission form.

---

## Record Triggered Flow

Record Triggered Flow runs automatically when a record is created, updated, or deleted.

Example:
Automatically send email when student registration is completed.

---

# 3. Automation Ideas

## 1. Auto Email After Registration

When a student registers, an automatic confirmation email is sent.

### Why automation helps?
Saves manual effort and improves communication.

---

## 2. Generate Student ID Automatically

Student ID is created automatically after admission.

### Why automation helps?
Avoids duplicate IDs and reduces manual work.

---

## 3. Update Remaining Seats Automatically

Course seats reduce automatically after each registration.

### Why automation helps?
Keeps seat availability accurate.

---

## 4. Notify Faculty When Course Is Full

Faculty receives notification when seats are full.

### Why automation helps?
Improves course management.

---

## 5. Send Fee Deadline Reminder

Students receive reminders before fee due date.

### Why automation helps?
Reduces late payments.

---

# 4. Flow Diagram

## Process: Student Registration Automation

Trigger:
Student record created

↓

Check:
Are seats available?

↓

If YES:
- Register student
- Reduce remaining seats
- Send confirmation email

↓

If NO:
- Show "Course Full" message

(Add diagram image here)

---

# 5. Manual vs Automated Process

## Manual Process

Staff manually:
- Check seat availability
- Send emails
- Update records

### Problems
- Time consuming
- Human errors
- Delays

---

## Automated Process

Salesforce automatically:
- Checks seats
- Sends notifications
- Updates records instantly

### Benefits
- Faster work
- Better accuracy
- Improved productivity

---

# 6. Reflection

## Why Automation Matters

Companies automate repetitive tasks to save time, reduce mistakes, improve consistency, and increase productivity. Automation allows employees to focus on more important work instead of repeating the same tasks manually.

---
