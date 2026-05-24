# INVU-BUG-003 — Registration Form Submits Without Showing Validation Error When Email Field Is Empty

## Environment
- **Test Device**: Laptop, Microsoft Surface 4
- **Operating system**: Microsoft Windows 11 Pro 10.0.26100
- **Browser**: Microsoft Edge Version 142.0.3595.94
- **Reproducibility**: 100%

## Severity / Priority
- **Severity:** Critical
- **Priority:** High

## Preconditions
- User has navigated to **https://invu.ge**
- User is **not logged in** — if a session exists, log out before starting
- The Register / Sign Up button is visible on the page

## Steps to Reproduce
1. Open **https://invu.ge**
2. Click the **Register / Sign Up** button
3. Leave the **Email** field completely empty
4. Enter a valid password in the **Password** field — e.g. `Test@1234`
5. Enter the same value in the **Confirm Password** field — e.g. `Test@1234`
6. Click the **Register / Submit** button

## Expected Result
The form should prevent submission and display a clear inline validation error on the Email field — e.g. **"Email is required"** or **"Please enter your email address"**. The error should appear immediately without a network request being made.

## Actual Result
The form does not validate the empty Email field. The submit button triggers a loading spinner for approximately 1–2 seconds, after which the page reloads silently. No error message is displayed. No account is created. The user is left on a blank form with no explanation of what went wrong.
