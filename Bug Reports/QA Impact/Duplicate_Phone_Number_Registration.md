# Duplicate Registration Allowed with Same Phone Number

## Enviroment
- Test Device: Laptop, Microsoft Surface 4
- Operating system: Microsoft Windows 11 Pro 10.0.26100
- Browser: Microsoft Edge Version 142.0.3595.94
- Reproducibility: 100%
  
## Severity / Priority
- Severity: Critical
- Priority: High

## steps to reproduce:
- Open the website https://hrthoth.com/
- Click on registration
- Click on "Candidate"
- Fill in the given fields and enter the phone number in the field (e.g. 599099002)
- Complete the registration
- After creating the account, exit the website
- Repeat the same steps to create a new account and enter the same number in the phone number field

## Excepted result:
- The system should prevent duplicate registration using the same phone number.
- A message should appear, for example:
  "This phone number is already registered. Please log in or use a different number."

## Actual result:
The system allows creating a new account with the same phone number.

## Attachments:
https://jam.dev/c/ed3a674a-5e45-42b8-b45b-be93918e9a9f
