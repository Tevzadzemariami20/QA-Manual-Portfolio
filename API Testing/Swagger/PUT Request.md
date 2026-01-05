# PUT Request
## Overview
This document describes a PUT request used in manual API testing to update an existing resource.
The request validates request body handling, successful update behavior, and response data accuracy.

## Request Details
- Method: PUT
- URL: https://reqres.in/api/custom-endpoints/2
- Headers	Content-Type: application/json
- Authorization: API Key (x-api-key)
- Request Body: JSON

## Expected Result
Status code: 200 OK
Resource is successfully updated
Response body contains:
- Updated name
- Updated job
- updatedAt timestamp in ISO 8601 format
Response is returned in JSON format

## Actual Result
Status code: 200 OK
API successfully updated the resource
Response body returned updated fields and update timestamp

```json
{
  "name": "John Doe",
  "job": "QA Tester",
  "updatedAt": "2025-12-18T19:53:31.181Z"
}
