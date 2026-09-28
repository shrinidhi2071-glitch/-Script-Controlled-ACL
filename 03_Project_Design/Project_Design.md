# Project Design

## System Design

The project consists of the following components:

**User → Roles → Institution Details Table → ACLs → Access Control**

## User

A test user is created:

- **User ID:** `EEE User`
- **First Name:** EEE
- **Last Name:** User
- **Email:** `eeeuser@gmail.com`

## Roles

Four custom roles are created:

- `bb1` – READ
- `bb2` – CREATE
- `bb3` – WRITE
- `bb4` – DELETE

The required roles are assigned to the test user.

## Institution Details Table

**Table Name:** `u_institution_details`

**Label:** Institution Details

The table stores student information such as:

- Student Roll Number
- Student Name
- Faculty Name
- Branch
- Email
- Phone Number
- Description

## ACL Design

The ACL structure is:

Institution Details

- READ → `bb1`
- CREATE → `bb2`
- WRITE → `bb3`
- DELETE → `bb4`

Administrators retain full access.

## Project Team

**Team Leader:** Sakthi Shrinidhi C

**Team Members:**
- Meenakshi S
- K Srividhya
- Swarna Priya A
