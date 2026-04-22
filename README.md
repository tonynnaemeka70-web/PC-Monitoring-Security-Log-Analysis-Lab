PC Monitoring & Security Log Analysis Lab (SOC Simulation)

Project Overview

This project simulates a Security Operations Center (SOC) monitoring environment where system logs are collected, analyzed, and investigated to detect suspicious activity and potential security incidents.

seconddly it demonstrates basic security monitoring on a Windows PC using [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) and Windows Event Viewer. It was completed as part of my cybersecurity learning journey.


The objective is to demonstrate practical skills in:
Log analysis and interpretation
Incident detection and response simulation
Security monitoring workflows used in SOC environments

2.  Tools Used
- **Sysmon64 v15.15** – System activity monitor from Sysinternals
- **Windows Event Viewer** – Built-in Windows log viewer
- **Configuration File:** `sysmonconfig-export.xml` from [SwiftOnSecurity](https://github.com/SwiftOnSecurity/sysmon-config)

3.  Objectives
- Install and configure Sysmon
- Generate and analyze logs for:
  - Process creation
  - PowerShell activity
  - Failed login attempts
- Write a short incident report with security recommendations

4. Screenshots
   
Screenshots are stored in the `/assets` folder:

- `screenshot_sysmon_operational.png`
- `screenshot_security_failed_login.png`
- `screenshot_powershell_activity.png`

5 Report

See [`Sysmon Security Monitoring Lab Report`](Sysmon%20Security%20Monitoring%20Lab%20Report.md)

for full details on setup, findings, and recommendations.

AUTHOR

Tony Nnaemeka- cyber security specialist and SOC Analyst

