# SOC-Lab (Home Security Operations Lab)

This project simulates a basic SOC environment using Splunk and Windows logs to detect suspicious activity.

# 🔍 What I Built
- Ingested Windows Event Logs and Sysmon into Splunk using a Universal Forwarder.
- Built dashboards to monitor:
  - PowerShell execution 
  - Windows logon failures (Event ID 4625)
  - Log ingestion trends over time

# ⚙️ Tools Used
- Splunk Free Edition
- Universal Forwarder
- Sysmon
- Windows 11 (as the victim endpoint)
- Kali Linux (Hydra brute force login simulation)

# 📸 Dashboards
- Suspicious PowerShell Activity
- Log Ingestion Breakdown
- Sysmon Event ID Volume Over Time

# 💡 What I Learned
- How to simulate log events with attack tools (Hydra)
- Use of `spath`, `stats`, and `table` in SPL
- Creating dashboards and alerts in Splunk

#📸 Screenshots

# Dashboard Overview
![dashboard-overview](https://github.com/user-attachments/assets/14b4aa08-8d89-4f37-9067-2e006e357938)

# Detection of Potential Malicious PowerShell Activity 
![powershell-activity](https://github.com/user-attachments/assets/e991efae-f532-4bd9-b96b-ac072b450d39)

# Event ID Volume Over Time
![event-id](https://github.com/user-attachments/assets/6b9eab99-0776-4a4e-bb23-13a30f9cb907)

# Log Ingestion Breakdown Over Time
![log-ingestion](https://github.com/user-attachments/assets/e51a78a6-584f-4055-b192-2ee19f4cfe8d)
