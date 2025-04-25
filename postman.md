Postman API Inspection

API Call Summary

Method:POST  
Endpoint:https://api.linqapp.com/api/v2/contacts  

Request Headers

Content-Type: application/json
Authorization: Bearer <token>

Request Body (Payload)

json
{
  "first_name": "John",
  "last_name": "Doe",
  "phone_number": "1234567890",
  "email": "john.doe@example.com",
  "company": "Linq Technologies",
  "title": "QA Analyst",
  "location": "Montgomery, AL",
  "image_url": "https://example.com/john-doe.jpg",
  "override_hr_synced": true
}

Response Summary

Status: 200 OK  
Time:94 ms  
Size:1.54 KB

Response Body:

json
{
  "contact": {
    "id": 2581635,
    "first_name": "John",
    "last_name": "Doe",
    "phone_number": "1234567890",
    "location": "Montgomery, AL",
    "email": "john.doe@example.com",
    "company": "Linq Technologies",
    "title": "QA Analyst",
    "image_url": "https://example.com/john-doe.jpg",
    "deleted_at": null
  }
}

 Findings & Observations

The contact was successfully saved and returned in the response with a unique `id`.
Fields in the response accurately match the request data.
HTTP 200 confirms successful request processing.
