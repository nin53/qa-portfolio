# 🐞 BUG-001

## Summary
**Unknown Error** message is displayed when changing the password using valid data.

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
2. User is registered.
3. User is logged into the system.

---

## Steps to Reproduce

1. Open the Profile page.
2. Enter the current valid password.
3. Enter a new password.
4. Enter the same password in the **Confirm Password** field.
5. Click **Save**.

---

## Actual Result

The message **"Unknown Error"** is displayed.

---

## Expected Result

The password is successfully changed and a confirmation message is displayed.

---

## Severity

🟡 Medium

---

## Priority

🟡 Medium

---

## Attachment

**Screenshot**

`screenshot.png`
