# servicenow-portfolio
Contains all of my custom applications built while learning ServiceNow development.

---

## Overview

This portfolio contains custom applications that I have built and linked to source 
control via ServiceNow Studio. These applications have been built in the context of 
the ServiceNow Certified System Administrator (CSA) and Certified Application Developer 
(CAD) qualifications, as a way of getting hands-on experience building real, functional 
applications rather than following isolated exercises.

---

## Technologies used

- ServiceNow Personal Developer Instance (Zurich release)
- JavaScript, including ServiceNow Now Platform APIs (GlideRecord, GlideSystem, g_form)
- ServiceNow Studio source control integration
- VS Code with ServiceNow extension for local script sync
- Git and GitHub for version control

---

## Custom applications

**Cyber Incident Management** — a custom scoped application for managing cyber 
security incidents, aligned to Australian Cyber Security Centre (ACSC) standards. 
Access is restricted to Major Incident Management and Cyber Security team personnel.

---

## Accessing the applications

These applications require a ServiceNow instance to run. Explore the code by browsing 
this repository — all application files are contained here in ServiceNow's native format.

To import an application into your own ServiceNow PDI, contact me for update set XMLs.
Alternatively, I can grant temporary read access to my PDI with the running applications.

---

## Repository structure

This repository is managed via ServiceNow Studio source control integration. Files are 
stored in ServiceNow's native XML format organised by update set structure — this is the 
standard format for transporting and importing applications between ServiceNow instances.

For readable scripts and a documented learning journey, see the companion 
repo: **servicenow-cyber-incident-app** (available on request).

```
servicenow-portfolio/
├── [application-folder]/
│   ├── author_elective_update/    # Application configuration records
│   ├── dictionary/                # Table and field definitions
│   └── update/                    # Application update records
└── README.md
```

---

## Design decisions

### Cyber Incident Management
- Custom fields aligned to Australian Cyber Security Centre (ACSC) definitions 
  and the ACSC Essential Eight framework.
- Extended from the task table rather than the incident table — this isolates 
  cyber incident records from standard ITSM queues, ensuring sensitive security 
  data is not visible to general IT staff.
- Access restricted via custom roles and ACLs to MIM and Cyber Security 
  team personnel only.
- Notification routing aligned to Australian regulatory obligations including 
  the Privacy Act 1988, the Notifiable Data Breaches scheme, and the Security 
  of Critical Infrastructure Act 2018 (SOCI Act).

---

## Future work

- Cyber Incident Management application is still in progress — CAD phase 
  scripting and automation labs ongoing.
- Business Impact Assessment application — standalone multi-table app for 
  structured BIA during major incidents.

---

## Author

Eric Carroll

ITIL v4 Major Incident and Problem Management process lead transitioning 
into ServiceNow development. Bringing process governance experience into 
a technical delivery role.
