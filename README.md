# Script-Controlled ACL – Restrict Record Access Based on Field Value

## Project Overview

This project demonstrates how ServiceNow Access Control Lists (ACLs) can be used to control access to records based on user roles and field values.

The project uses a custom **Institution Details** table and separate roles for READ, CREATE, WRITE, and DELETE operations.

## Project Objective

The main objective of this project is to implement record-level security in ServiceNow using ACLs and scripts.

The READ access is further controlled using a field condition so that EEE branch records can be restricted according to the configured access rules.

## Technology Used

- ServiceNow
- Access Control Lists (ACL)
- JavaScript
- ServiceNow Roles
- Custom Tables

## Access Control

| Operation | Role |
|---|---|
| READ | `bb1` |
| CREATE | `bb2` |
| WRITE | `bb3` |
| DELETE | `bb4` |
| Full Access | `admin` |

## Institution Details Table

**Table Name:** `u_institution_details`

### Fields

- Student Roll Number
- Student Name
- Faculty Name
- Branch
- Email
- Phone Number
- Description

### Branch Choices

- ECE
- EEE
- CSE

## Project Phases

The project is organized into eight phases:

1. [Brainstorming and Ideation](01_Brainstorming_and_Ideation/Brainstorming_and_Ideation.md)
2. [Requirement Analysis](02_Requirement_Analysis/Requirement_Analysis.md)
3. [Project Design](03_Project_Design/Project_Design.md)
4. [Project Planning](04_Project_Planning/Project_Planning.md)
5. [Project Development](05_Project_Development/Project_Development.md)
6. [Project Testing](06_Project_Testing/Project_Testing.md)
7. [Project Documentation](07_Project_Documentation/Project_Documentation.md)
8. [Project Demonstration](08_Project_Demonstration/Project_Demonstration.md)

## Team Members

### Team Leader

**Sakthi Shrinidhi C**

### Team Members

- **Meenakshi S**
- **K Srividhya**
- **Swarna Priya A**

## Work Distribution

| Task | Assigned To |
|---|---|
| User Creation | Meenakshi S |
| Roles Creation | K Srividhya |
| Table Creation | Swarna Priya A |
| READ ACL | K Srividhya |
| CREATE ACL | Sakthi Shrinidhi C |
| WRITE ACL | Meenakshi S |
| DELETE ACL | Swarna Priya A |
| Project Outcome | Sakthi Shrinidhi C |

## Project Outcome

The project successfully demonstrates role-based and field-based record access control using ServiceNow ACLs.

It shows how different user roles can be used to control READ, CREATE, WRITE, and DELETE operations on records.

## Demo Video

**Demo Video Link:**  
Paste your Google Drive or YouTube demo video link here.

## GitHub Repository

**Repository:**  
https://github.com/shrinidhi2071-glitch/-Script-Controlled-ACL.git
