# INVU-BUG-001 — Invitation Preview Does Not Update in Real Time When Editing the Message Field

## Environment
- **Test Device**: Laptop, Microsoft Surface 4
- **Operating system**: Microsoft Windows 11 Pro 10.0.26100
- **Browser**: Microsoft Edge Version 142.0.3595.94
- **Reproducibility**: 100%

## Severity / Priority
- **Severity:** Major
- **Priority:** High

## Preconditions
- User is logged in to **https://invu.ge**
- User has opened the Invitation Constructor page
- An invitation template has been selected
- The Edit Text form is open and all fields are visible

## Steps to Reproduce
1. Click **Edit Text** on the Invitation Constructor page
2. Type a value in the **Name 1** field — e.g. `Ana` — and observe the preview updates instantly
3. Click the **Message** field and begin typing — e.g. `You are invited to our wedding!`
4. Observe the invitation preview panel **while actively typing** in the Message field

## Expected Result
The preview panel should update in real time as the user types in the Message field — consistent with the live-update behaviour of all other fields on the same form (Name 1, Name 2, Location, Date, Time).

## Actual Result
The preview panel does **not** update while the user is typing in the Message field. It only refreshes after the user clicks outside the field. During typing, the preview continues to show the previous message value or remains blank.

