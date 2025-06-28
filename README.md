# SOC-Lab (Home Security Operations Lab)

This project simulates a basic SOC environment using Splunk and Windows logs to detect suspicious activity.

## 🔍 What I Built
- Ingested Windows Event Logs and Sysmon into Splunk using a Universal Forwarder.
- Built dashboards to monitor:
  - PowerShell execution (e.g., `powershell_ise.exe`)
  - Windows logon failures (Event ID 4625)
  - Log ingestion trends over time

## ⚙️ Tools Used
- Splunk Free Edition
- Universal Forwarder
- Sysmon
- Windows 10 (as the victim endpoint)
- Kali Linux (Hydra brute force login simulation)

## 📸 Dashboards
- **Suspicious PowerShell Activity**
- **Log Ingestion Breakdown**
- **Sysmon Event ID Volume Over Time**

## 💡 What I Learned
- How to simulate log events with attack tools (Hydra)
- Use of `spath`, `stats`, and `table` in SPL
- Creating dashboards and alerts in Splunk

## 📁 Contents
- `screenshots/` – visual proof of dashboards
- `splunk-queries.txt` – the SPL searches used
