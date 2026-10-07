# Initial Data Model

## Student
- id
- memberId
- fullName
- email
- phone
- institution
- programme
- level
- profile data
- createdAt
- updatedAt

## Partner
- id
- organizationName
- description
- contact information
- access status

## Content
- id
- authorId
- type
- title
- body/media reference
- publication status
- createdAt

## Event
- id
- title
- description
- date/time
- location or online details
- organizer
- status

Sensitive credentials and authentication secrets must never be stored in client-side source code.
