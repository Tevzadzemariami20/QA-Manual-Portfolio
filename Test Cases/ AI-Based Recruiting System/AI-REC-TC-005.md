# AI-REC-TC-005 – Verify Empty Prompt Cannot Be Sent

#### Priority: Medium  
#### Type: Functional  
#### Feature: Prompt / Chat  
#### Status: Pass  

## Description
- Verify that the system does not allow the user to send an empty prompt using either the **Send** button or the **Enter** key.

## Pre-conditions
- User is registered
- User is logged in
- User has access to the chat dashboard

| Step No. | Action | Expected Result |
| -------- | ------ | --------------- |
| 1 | Navigate to https://getbot.ai | The website opens successfully |
| 2 | Log in to the application | User is logged in successfully |
| 3 | Navigate to the chat dashboard | Chat dashboard is displayed |
| 4 | Ensure the chat input field is empty | Chat input field is empty |
| 5 | Click the **Send** button | The prompt is not sent |
| 6 | Press the **Enter** key | The prompt is not sent and no message appears |

## Post-conditions
- No empty message is sent
- Chat remains unchanged
- The system prevents invalid input submission
