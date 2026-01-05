# POST Request

## Overview
This document describes a POST request used in manual API testing to create a new resource.
The request validates request body handling, response status codes, and correct data creation behavior when valid input is provided.

## Request Details
- Method: POST
- URL: https://reqres.in/api/custom-endpoints
- Headers: Content-Type: application/json
- Authorization: API Key (x-api-key)
- Request Body: JSON

## Expected Result
Status code: 201 Created
Response body contains:
-Automatically generated id
-createdAt timestamp indicating when the resource was created
Response is returned in JSON format

## Actual Result
Status code: 201 Created
API successfully created a new resource
Response body returned only the generated identifier and creation timestamp

```json
{
    "id": "914",
    "createdAt": "2025-12-18T19:07:12.469Z"
}


