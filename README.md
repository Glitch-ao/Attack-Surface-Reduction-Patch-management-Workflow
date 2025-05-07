# Vulnerability Patching & Attack Surface Management

This project focused on managing vulnerabilities by implementing systematic patching techniques and reducing the attack surface of both Windows and Linux systems. I worked on setting up production workstations, enforcing update policies via Group Policy, and automating updates using scripts and scheduled tasks.

## Tags
`Patch Management` `Windows Update Policy` `Linux Updates` `Group Policy` `Attack Surface Reduction`

---



### Windows Patch Management
- Created a **Windows production workstation** for testing patch management
- Developed a **Group Policy Object (GPO)** to configure automatic updates:
  - Set schedule for download and install
  - Forced restart behavior after update
  - Blocked users from disabling updates
- Created a **PowerShell update script** using `Get-WindowsUpdate` and `Install-WindowsUpdate` (with PSWindowsUpdate module)
- Configured a **Scheduled Task** to run the update script at 3 AM every Sunday

### Linux Patch Management
- Set up a **Linux (Ubuntu) workstation**
- Configured `unattended-upgrades` for automatic security updates
- Created a custom **Bash script** using `apt update && apt upgrade -y`
- Scheduled updates using `cron` to run weekly

---

## Learning Outcomes

After completing this project, I was able to:

- Create secure production workstations on both Windows and Linux
- Implement Windows patching via Group Policy and PowerShell scripting
- Automate patching tasks with scheduled tasks (Windows) and cron jobs (Linux)
- Reduce potential attack vectors by maintaining updated systems

---

## Tools & Technologies Used

- **Group Policy Editor (gpedit.msc)**
- **PowerShell** – Patch scripting and task scheduling
- **Scheduled Tasks (taskschd.msc)**
- **Ubuntu/Debian Linux**
- **Bash scripting**
- **Cron**
- **PSWindowsUpdate module**

---

## Sample Artifacts
*(Include screenshots or code snippets of the GPO settings, PowerShell script, Linux update script, and task schedulers if available)*

