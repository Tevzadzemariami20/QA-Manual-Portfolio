# GET Requests

## Overview
This document describes a GET request used in manual API testing to retrieve details of a specific user by ID.
The example focuses on validating successful data retrieval, correct response structure, and proper authorization handling. Each request includes the HTTP method, endpoint URL, required headers, and expected response behavior.

## Request Details
- Method: GET
- URL: https://reqres.in/api/{resource}/2
- Authorization: API Key (x-api-key)
- Headers	Content-Type: application/json
- Request Body:Not required

## Expected Result
- Status code: 200 OK

Response contains:
- id
- name
- year
- color
- pantone_value
- Response time is within acceptable limits

## Actual Result

- Status code: **200 OK**
- Response body returned correct resource details:

```json
{
  "data": {
    "id": 2,
    "name": "fuchsia rose",
    "year": 2001,
    "color": "#C74375",
    "pantone_value": "17-2031"
  }
}

