# HealthSync Access Control

HealthSync uses role-based access control (RBAC) so users only have access to the information and functions they need for their role.

## User Roles

### Patient

Patients have access to their own information through the patient portal.

They can:

- View appointments
- View available lab results
- View prescription information
- Receive system notifications

Patients cannot access another patient's records or administrative functions.

### Doctor / Nurse

Clinical staff need access to patient information for their work.

They can:

- View assigned patient records
- Review lab results
- Update clinical information
- Submit lab and prescription requests
- View relevant patient and appointment information

Their access does not include system administration.

### Administrative Staff

Administrative users handle the non-clinical side of hospital operations.

They can:

- Register patients
- Manage appointments
- Update demographic information
- Work with billing and insurance information
- View information needed for administrative tasks

Clinical information should only be available when it is required for the user's job.

### IT / System Administrator

System administrators manage the technical environment rather than patient care.

They can:

- Manage user accounts and roles
- Configure system access
- Monitor system activity
- Review technical and security logs
- Maintain system services

Administrative access should be limited to authorized IT personnel.

## Access Control Approach

Permissions are assigned according to a user's role instead of giving every account the same level of access.

This helps separate clinical, administrative, patient, and technical responsibilities. It also reduces unnecessary access to sensitive information.

User activity should be logged so important actions and access attempts can be reviewed when needed.
