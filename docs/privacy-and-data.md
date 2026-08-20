# Privacy and Data Strategy

> Privacy-conscious data handling principles for the Ayur Clinic website.

## Overview

Ayur Clinic is a healthcare-focused platform, which means privacy and responsible data handling are considered from the beginning of the project.

The current website is primarily informational. A key architectural decision is to avoid collecting unnecessary personal or sensitive information through the public website.

The core principle is:

> Collect only the information that is genuinely required for a clearly defined purpose.

This approach reduces unnecessary privacy risk and keeps the initial platform focused on providing clear information and patient resources.

---

## Data Minimisation

The website should not collect information simply because it may be useful in the future.

Any data collection must have a specific purpose.

For the informational website, most users should be able to access:

- Clinic information
- Services
- Team information
- Patient resources
- Pregnancy tools
- Location information
- Parking guidance

without providing personal information.

---

## Sensitive Health Information

The general public website is intentionally designed to avoid collecting sensitive health information through standard contact or callback forms.

This includes avoiding unnecessary collection of:

- Medical history
- Symptoms
- Diagnoses
- Treatment details
- Pregnancy complications
- Other clinical information

A general website contact form should not become an uncontrolled channel for patients to submit sensitive medical information.

If future functionality requires the collection of health-related information, that workflow will need to be designed and evaluated separately.

---

## Future Contact and Callback Requests

Future contact or callback functionality should follow a data-minimisation approach.

The intended workflow may collect only the information required for the clinic to respond.

Potential fields include:

- Full name
- Email address
- Phone number

The exact fields will depend on the final purpose of the workflow.

Open-ended text fields requesting medical information should be avoided unless there is a clearly defined and appropriately designed workflow for handling that information.

---

## Planned Data Flow

Where a future contact or callback workflow is introduced, the intended flow is:

```text
Patient
   │
   ▼
Validated Request
   │
   ▼
Controlled Server-Side Processing
   │
   ▼
Secure Database
   │
   ▼
Authorised Clinic Access
