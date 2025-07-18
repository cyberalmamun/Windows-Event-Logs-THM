# 🪵 TryHackMe – Windows Event Logs

This repository documents my hands-on experience from the [TryHackMe room: Windows Event Logs](https://tryhackme.com/room/windowseventlogs). The room focuses on using **Windows Event Viewer** for analyzing logs that are critical for incident response and blue team operations.

---
## 🔍 Task Highlight – Task 2: Event Viewer

In this task, I explored how Windows logs are stored and analyzed, particularly through the **Microsoft-Windows-PowerShell/Operational** log.

### 🧠 Key Activities:
- Opened **Event Viewer** (`eventvwr.msc`) and navigated to `Applications and Services Logs > Microsoft > Windows > PowerShell > Operational`
- Reviewed log structure: Level, Date/Time, Source, Event ID, Task Category
- Analyzed the earliest recorded event in the log
- Filtered for **Event ID 4104** to inspect specific PowerShell command executions
- Identified PowerShell activities such as the `whoami` command
- Investigated **Event ID 800** to determine its Task Category
- Understood log rotation, clearing logs, and event filtering via the **Action pane**


### 🔐 Tools Used:
- ✅ RDP access to Windows machine (via Kali Linux + `xfreerdp`)
- ✅ Windows Event Viewer
- ✅ TryHackMe VPN for secure connection to lab machine

---

## 📸 Screenshots

All evidence and screenshots of log analysis are included in the [`screenshots/`](screenshots/) folder.

---

## 🧩 Skills Demonstrated
- Windows log analysis (PowerShell Operational logs)
- Event filtering using Event ID and Task Category
- Blue team investigation workflows
- Familiarity with event log structure and XML view
- Identifying artifacts of PowerShell activity for forensic triage

---

## 🚀 Room Link

🔗 [Windows Event Logs – TryHackMe](https://tryhackme.com/room/windowseventlogs)

---

## 📁 Screenshots
<img width="1897" height="994" alt="Screenshot 2025-07-15 at 10 47 13 PM" src="https://github.com/user-attachments/assets/d8c8838f-ab70-4d25-ba88-7a5d86c5b7a5" />
<img width="1897" height="994" alt="Screenshot 2025-07-15 at 10 47 04 PM" src="https://github.com/user-attachments/assets/5e9063d4-2f16-479d-a6e4-d329f1c44887" />
<img width="1688" height="964" alt="Screenshot 2025-07-16 at 11 16 43 PM" src="https://github.com/user-attachments/assets/57a0905e-82ea-49e0-82c8-d8e885a1be13" />
<img width="1688" height="964" alt="Screenshot 2025-07-16 at 11 27 09 PM" src="https://github.com/user-attachments/assets/653244b9-11dd-4b64-a936-3d5ab13588a0" />
<img width="1688" height="964" alt="Screenshot 2025-07-16 at 11 26 54 PM" src="https://github.com/user-attachments/assets/f13d78bb-27ab-4bab-8ca8-2b5ff69a928a" />
<img width="1906" height="1034" alt="Screenshot 2025-07-16 at 11 29 27 PM" src="https://github.com/user-attachments/assets/86d9b1e0-cc4f-45ac-be20-5f7442018843" />





