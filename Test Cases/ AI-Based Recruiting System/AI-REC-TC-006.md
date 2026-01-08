# AI-REC-TC-006 – Verify that the Scan Button Works Correctly

#### Priority: High  
#### Type: Functional  
#### Feature: AI Plagiarism  
#### Status: Fail  

## Description
- Verify that the **Scan** button works correctly after the user enters a valid title and text on the AI Plagiarism page.

## Pre-conditions
- User is registered
- User is logged in
- User has access to the AI Plagiarism feature

| Step No. | Action | Expected Result |
| -------- | ------ | --------------- |
| 1 | Navigate to (Confidential) | The website opens successfully |
| 2 | Log in to the application | User is logged in successfully |
| 3 | Navigate to the **AI Plagiarism** page | AI Plagiarism page is displayed |
| 4 | Enter a valid title in the title field | Title is entered successfully |
| 5 | Enter a valid text in the text field | Text is entered successfully |
| 6 | Click the **Scan** button | The system starts the plagiarism scan and displays the scan results |

## Actual Result
- The **Scan** button does not work as expected after entering valid title and text.
- No scan results are displayed.

## Post-conditions
- Plagiarism scan is not initiated
- User is unable to view plagiarism results
