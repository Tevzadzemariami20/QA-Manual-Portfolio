# INVU-BUG-002 — Button Text Overflows Container After Switching Interface Language from EN to KA

## Environment
- **Test Device**: Laptop, Microsoft Surface 4
- **Operating system**: Microsoft Windows 11 Pro 10.0.26100
- **Browser**: Microsoft Edge Version 142.0.3595.94
- **Reproducibility**: 100%

## Severity / Priority
- **Severity:** Minor
- **Priority:** Medium

## Preconditions
- User has navigated to **https://invu.ge**
- Page has loaded successfully with no errors
- Language switcher showing **EN** and **KA** is visible in the header

## Steps to Reproduce
1. Open **https://invu.ge**
2. Confirm the page is displayed in English (EN is active on the language switcher)
3. Locate the primary CTA button on the homepage — e.g. **"Create Invitation"** — and note that the label fits correctly inside the button
4. Click **KA** on the language switcher
5. Locate the same button, now displaying the Georgian label
6. Observe the button label and its container

## Expected Result
The button should expand in width or height to fully contain the Georgian label text. No text should be clipped, wrapped onto a second line, or overflow the button boundary — consistent with how the EN version renders.

## Actual Result
The Georgian button label wraps onto two lines or is partially clipped by the button boundary. The button container does not expand to accommodate the longer Georgian text. The overflow is clearly visible at 1440×900 viewport width without scrolling.
