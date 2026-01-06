# AI-REC-TC-001 - Verify Chat Search Filters

#### ID: TC-ChatSearch-002
#### Priority: Medium  
#### Type: Functional  
#### Feature: Chat List & Chat Groups  
#### Status: Pass 

## Description
- Verify that the chat search functionality correctly filters and displays chats based on the entered keyword.

## Pre-conditions
- User is registered
- User is logged in
- User has access to the chat dashboard

| Step No.	| Action | Expected Result |
| --------	| ------ | ----------------|
| 1	| Navigate to https://getbot.ai | The website opens successfully |
| 2	| Log in to the application | User is logged in successfully |
| 3	| Navigate to the chat dashboard |Chat dashboard is displayed |
| 4	| Enter a keyword into the chat search field | Chat list is filtered based on the entered keyword and matching chats are displayed correctly|

## Post-conditions
- Search results match the entered keyword
- Non-matching chats are not displayed
