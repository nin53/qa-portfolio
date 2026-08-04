# 🐞 BUG-006

## Summary

The Age field accepts alphabetic characters.

---

## Environment

| Parameter | Value |
|-----------|-------|
| Device | Samsung Galaxy A24 |
| OS | Android 16 |
| Browser | Google Chrome Mobile 149.0.7827.59 |
| Website | https://buggy.justtestit.org |

---

## Preconditions

1. Open the website: https://buggy.justtestit.org
2. User is logged into the system.
3. Open the Profile page.

---

## Steps to Reproduce

1. Enter **"abc"** into the **Age** field.
2. Click **Save**.

---

## Actual Result

The system accepts alphabetic characters in the Age field and does not display a validation error.

---

## Expected Result

The Age field should accept only numeric values. If alphabetic characters are entered, the system should display a validation error and prevent saving.

---

## Severity

🟡 Medium

---

## Priority

🟡 Medium

---

## Attachment

**Screenshot**

![Screenshot](BUG-006.png)
