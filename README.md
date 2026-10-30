# servicenow-studio-cyb-inc-app

ServiceNow Studio source control for my Cyber Incident Management scoped application. Studio commits here directly from my personal developer instance.

**Full documentation is in [servicenow-updateset-cyb-inc-app](https://github.com/eric-t-carroll/servicenow-updateset-cyb-inc-app)**, including screenshots, design decisions, install steps, the lab index and build notes.

## What's here

The app is a custom scoped application for managing cyber incidents in line with Australian Cyber Security Centre (ACSC) guidance. It runs incidents through the Cyber Incident lifecycle (Investigation and Diagnosis, Containment, Eradication, Recovery) and creates regulatory notification tasks for the SOCI Act, the Cyber Security Act (ransomware payments) and the Privacy Act (notifiable data breaches). Access is restricted by roles and ACLs to Major Incident Management, Cyber Analyst and Legal roles.

## Installing

1. Create a GitHub personal access token for your own account (classic token with read access).
2. Create a Basic Auth credential in your ServiceNow instance, using your GitHub username and the token as the password.
3. In ServiceNow Studio > click the `Create` button drop down and select `Import App` > paste in this repo's URL > update branch to `main`, select your credential > `import app`.
4. Group and role setup, plus optional sample data, are covered in the **[main repo's README](https://github.com/eric-t-carroll/servicenow-updateset-cyb-inc-app)**.

## Author

Eric Carroll. ITSM process specialist moving into ServiceNow development. [LinkedIn](https://www.linkedin.com/in/eric-t-carroll)