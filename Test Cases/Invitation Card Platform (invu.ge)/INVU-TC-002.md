# INVU-TC-002 — User Registration: Valid Inputs

| Field       | Value                          |
|-------------|--------------------------------|
| Test Type   | Functional / UI Validation     |
| Priority    | High                           |
| Module      | Authentication — Registration  |

---

## Description

Verify that a new user can successfully complete account registration using valid data, and that the system responds correctly after submission (redirect, success message, or verification email).

---

## Preconditions

- [ ] Navigate to **https://invu.ge** and confirm the page loads with no errors
- [ ] Confirm you are **not logged in** — if a session exists, log out first
- [ ] Confirm the **Register / Sign Up** button is visible in the header or homepage
- [ ] Prepare a **valid, unregistered email address** (e.g. `tester0@gmail.com`)
- [ ] Prepare a **valid password** that meets the site's requirements (e.g. `Test@1234` — min. 8 characters, mixed case and number)

---

## Test Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Click the **Register** or **Sign Up** button on the homepage | Registration form opens. All required fields are visible: email, password, confirm password. No errors are shown. |
| 2 | Enter a valid, unregistered email address in the **Email** field (e.g. `tester0@gmail.com`) | Email is accepted. No validation error is shown for this field. |
| 3 | Enter a valid password in the **Password** field (e.g. `Test@1234`) | Password is accepted. No validation error is shown. The field masks the input with dots or asterisks. |
| 4 | Enter the same password in the **Confirm Password** field (e.g. `Test@1234`) | Confirm password field accepts the input. No "passwords do not match" error is shown. |
| 5 | Fill in any other required fields with valid data (e.g. name, phone — if present on the form) | All fields accept the input without errors. The Submit button is active and not greyed out. |
| 6 | Click the **Register / Submit** button | Form submits successfully. A loading indicator may appear briefly. No error message is shown. |
| 7 | Observe the system response after submission | One of the following occurs — note which one: **(a)** user is redirected to a dashboard or homepage, **(b)** a success message is shown on screen, or **(c)** a prompt appears to check email for a verification link. Any of these is a passing result. |
| 8 | *(If step 7 result was option c)* Open the registered email inbox and click the **verification link** | The link opens successfully. The account is confirmed. User is redirected to login page or logged in automatically. |
| 9 | Navigate to the **Login** page and log in using the email and password registered in steps 2–3 | Login is successful. The user is authenticated and can access their account. |

---

## Postconditions

- [ ] New user account was created successfully
- [ ] User can log in with the registered credentials
- [ ] Actual post-registration behaviour from step 7 is noted in the test run log (redirect / success message / verification email)
