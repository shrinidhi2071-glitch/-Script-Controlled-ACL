# Project Testing

## Testing Overview

Testing was performed to verify that the configured ACLs work correctly and provide the required access based on roles and field conditions.

---

## Test Case 1 – READ Access

**User:** User with `bb1` role

**Operation:** Read

**Expected Result:** EEE branch records can be viewed.

**Result:** Passed.

---

## Test Case 2 – CREATE Access

**User:** User with `bb2` role

**Operation:** Create

**Expected Result:** User can create a new record.

**Result:** Passed.

---

## Test Case 3 – WRITE Access

**User:** User with `bb3` role

**Operation:** Write

**Expected Result:** User can modify records.

**Result:** Passed.

---

## Test Case 4 – DELETE Access

**User:** User with `bb4` role

**Operation:** Delete

**Expected Result:** User can delete records.

**Result:** Passed.

---

## Test Case 5 – Administrator Access

**User:** Administrator

**Operation:** Read / Write / Create / Delete

**Expected Result:** Administrator has full access.

**Result:** Passed.

---

## Testing Summary

| Test Case | Operation | Role | Result |
|---|---|---|---|
| 1 | READ | `bb1` | Passed |
| 2 | CREATE | `bb2` | Passed |
| 3 | WRITE | `bb3` | Passed |
| 4 | DELETE | `bb4` | Passed |
| 5 | Full Access | `admin` | Passed |

## Testing Conclusion

The configured ACLs successfully control access according to the assigned roles and field conditions. The testing confirms that READ, CREATE, WRITE, and DELETE operations are controlled as intended.

## Project Team

**Team Leader:** Sakthi Shrinidhi C

**Team Members:**
- Meenakshi S
- K Srividhya
- Swarna Priya A
