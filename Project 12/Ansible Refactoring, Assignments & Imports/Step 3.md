# REFERENCE WEBSERVER ROLE

Step 4 – Reference ‘Webserver’ role

Within the static-assignments folder, create a new assignment for uat-webservers uat-webservers.yml. This is where you will reference
the role.

```
---
- hosts: uat-webservers
  roles:
     - webserver
---


