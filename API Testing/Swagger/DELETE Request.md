# DELETE Request

## Overview
This document describes a DELETE request used in manual API testing to remove an existing user.
The request validates successful deletion behavior and correct HTTP status code handling.

## Request Details
- Method: DELETE
- URL: https://reqres.in/api/users/{id}/2
- Headers: Content-Type: application/json
- Authorization: API Key (x-api-key)
- Request Body: Not required

## Expected Result
Status code: 204 No Content
User is successfully deleted
Response body is empty

## Actual Result
- Status code: 204 No Content
- API successfully processed the delete request
- No response body returned
  
```json
(empty response body)

