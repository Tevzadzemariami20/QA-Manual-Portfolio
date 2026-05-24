# INVU-TC-003 — Invitation Constructor: Create Card by Filling In All Fields

| Field     | Value                         |
|-----------|-------------------------------|
| Test Type | Functional / UI Validation    |
| Priority  | High                          |
| Module    | Invitation Constructor        |

---

## Description

Verify that a user can fill in all available fields in the Invitation Constructor (Name 1, Name 2, Message, Location, Date, Time) using valid data, and successfully proceed to the next step. The preview should reflect all entered values in real time or upon save.

---

## Preconditions

- [ ] Navigate to **https://invu.ge** and confirm the page loads with no errors
- [ ] Confirm you are **logged in** — if not, log in before starting
- [ ] Navigate to the **Invitation Constructor** page
- [ ] Confirm the **Edit Text** button is visible on the page
- [ ] Confirm all fields are visible or become visible after opening the form: **Name 1, Name 2, Message, Location, Date, Time**

---

## Test Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Click the **Edit Text** button on the Invitation Constructor page | The Event Details form opens. All fields are visible: Name 1, Name 2, Message, Location, Date, Time. No errors are shown. |
| 2 | Click the **Name 1** field and enter a first name — e.g. `Ana` | The value `Ana` is displayed in the field. No validation error is shown. |
| 3 | Click the **Name 2** field and enter a second name — e.g. `Giorgi` | The value `Giorgi` is displayed in the field. No validation error is shown. |
| 4 | Click the **Message** field and enter a short message — e.g. `You are invited to our wedding!` | The full message text is displayed in the field. No validation error is shown. The field does not truncate or cut off the input. |
| 5 | Click the **Location** field and enter a location — e.g. `Tbilisi, Sheraton Hotel` | The location text is displayed in the field. No validation error is shown. |
| 6 | Click the **Date** field and select or enter a date — e.g. `20/09/2025` | The date is displayed in the field in the expected format (e.g. `dd/mm/yyyy`). No validation error is shown. |
| 7 | Click the **Time** field and enter a time — e.g. `18:00` | The time `18:00` is displayed in the field. No validation error is shown. |
| 8 | Look at the **invitation preview** area on the screen (if visible) and verify it reflects all entered values | The preview displays: Name 1 (`Ana`), Name 2 (`Giorgi`), Message, Location, Date, and Time — all matching what was entered in the fields. No field is blank or showing placeholder text. |
| 9 | Click the **Save**, **Next**, or **Continue** button | The page advances to the next step (e.g. photo upload or final preview). No error messages are shown. All entered data is preserved — no fields are reset. |

---

## Postconditions

- [ ] All fields accepted valid input without errors
- [ ] The invitation preview displayed all entered values correctly
- [ ] The user successfully advanced to the next step with no data loss
