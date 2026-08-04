# 🐞 BUG-005

## Summary

The user is not redirected to the login page after successful registration.

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
2. The user does not have an account with the selected username.

---

## Steps to Reproduce

1. Enter valid registration data.
2. Click **Register**.
3. Wait for the success message.

---

## Actual Result

A successful registration message is displayed, but the user remains on the registration page.

---

## Expected Result

After successful registration, the user should be automatically redirected to the Login page.

---

## Severity

🟢 Minor

---

## Priority

🟡 Medium

---

