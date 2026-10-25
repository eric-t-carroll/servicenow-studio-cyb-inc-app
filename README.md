# servicenow-studio-cyb-inc-app

ServiceNow Studio source control for my Cyber Incident Management scoped application. Studio commits here directly from my personal developer instance, so this repo always holds the current version of the application.

**Full documentation is in [servicenow-cyber-incident-app](https://github.com/eric-t-carroll/servicenow-cyber-incident-app)**, including screenshots, design decisions, install steps, the lab index and build notes.

## What's here

The app is a custom scoped application for managing cyber incidents in line with Australian Cyber Security Centre (ACSC) guidance. It runs incidents through the Cyber Incident lifecycle (Investigation and Diagnosis, Containment, Eradication, Recovery) and creates regulatory notification tasks for the SOCI Act, the Cyber Security Act (ransomware payments) and the Privacy Act (notifiable data breaches). Access is restricted by roles and ACLs to Major Incident Management, Cyber Analyst and Legal roles.

## Installing

In ServiceNow Studio, import the application from this repository's URL. Group and role setup, plus optional sample data, are covered in the main repo's README.

## Author

Eric Carroll. ITIL 4 Major Incident and Problem Management process lead moving into ServiceNow development. [LinkedIn](https://www.linkedin.com/in/eric-t-carroll)