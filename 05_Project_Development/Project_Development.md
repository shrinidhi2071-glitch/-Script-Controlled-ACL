# Project Development

## 1. User Creation

A ServiceNow user named **EEE User** was created.

### User Details

- **User ID:** `EEE User`
- **First Name:** EEE
- **Last Name:** User
- **Email:** `eeeuser@gmail.com`

**Performed by:** Meenakshi S

---

## 2. Role Creation

The following custom roles were created:

- `bb1`
- `bb2`
- `bb3`
- `bb4`

These roles are used to control different operations on the Institution Details table.

**Performed by:** K Srividhya

---

## 3. Table Creation

A custom table was created in ServiceNow.

**Table Name:** `u_institution_details`

**Label:** Institution Details

### Fields Created

- Student Roll Number – Auto Number
- Student Name – Reference User
- Faculty Name – Reference User
- Branch – Choice
- Email – String
- Phone Number – String
- Description – Multi String

### Branch Choices

- ECE
- EEE
- CSE

**Performed by:** Swarna Priya A

---

## 4. READ ACL

A Record READ ACL was configured for the Institution Details table.

**Table:** `u_institution_details`

**Operation:** Read

**Required Role:** `bb1`

The ACL uses a script to provide access while allowing administrators full access.

### ACL Script

```javascript
(function () {
    if (gs.hasRole('admin')) {
        return true;
    }

    if (gs.hasRole('bb1')) {
        return true;
    }

    return false;
})();
