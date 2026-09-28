# Brainstorming & Ideation

## Project Title

**Script-Controlled ACL – Restrict Record Access Based on Field Value**

## Problem Identification

In ServiceNow, controlling access to records is important for protecting sensitive information. Standard role-based ACLs may not always be sufficient when access needs to depend on a specific field value in a record.

For example, students belonging to the EEE branch should be able to access EEE-related records, while records belonging to other branches should have restricted access.

## Proposed Idea

The proposed project uses ServiceNow Access Control Lists (ACLs) and scripts to control access based on user roles and record field values.

The system provides separate permissions for:

- READ
- CREATE
- WRITE
- DELETE

## Main Idea

The project will:

1. Create users and custom roles.
2. Create a custom Institution Details table.
3. Add student and branch information.
4. Configure ACLs for different operations.
5. Use a script to control READ access.
6. Allow administrators to retain full access.
7. Test access using different users and roles.

## Expected Benefit

The project improves record security by allowing access to be controlled according to organizational requirements.

## Project Team

**Team Leader:** Sakthi Shrinidhi C

**Team Members:**
- Meenakshi S
- K Srividhya
- Swarna Priya A
