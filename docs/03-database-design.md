# Database Design

Version 1.0

## Entities

1. Users
2. Patients
3. Documents
4. Extractions
5. Diagnoses
6. Medications
7. Lab Results
8. Timeline Events
9. Audit Logs
10. Subscriptions

## Relationships

User
  └── Patients

Patient
  └── Documents

Document
  ├── Extractions
  ├── Diagnoses
  ├── Medications
  └── Lab Results

Patient
  └── Timeline Events

User
  └── Subscription

## Primary Keys

UUID

## Soft Deletes

Users

Patients

Documents

## Audit Requirements

Track:

Upload

Download

View

Edit

Delete

## Future Support

FHIR Mapping

Doctor Portal

Family Sharing

Mobile Applications
