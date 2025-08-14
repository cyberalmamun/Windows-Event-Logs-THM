# 🪵 TryHackMe – Windows Event This repository documents my hands-on experience from the [TryHackMe room: Windows Event Logs](https://tryhackme.com/room/windowseventlogs). 
The room focuses on using **Windows Event Viewer** for analyzing logs that are critical for incident response and blue team operations.


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
<img width="1915" height="966" alt="Screenshot 2025-08-01 at 5 11 53 PM" src="https://github.com/user-attachments/assets/2a8056f7-1f65-45b5-88d4-7ce1fbdd43b5" />
<img width="805" height="533" alt="Screenshot 2025-08-01 at 5 11 07 PM" src="https://github.com/user-attachments/assets/e88a8b35-d1ed-4e86-8b73-c0b05e46d83a" />
<img width="1915" height="966" alt="Screenshot 2025-08-01 at 5 21 49 PM" src="https://github.com/user-attachments/assets/a8563752-35a8-49cb-9f61-526b43888bf2" />
<img width="1915" height="966" alt="Screenshot 2025-08-01 at 5 22 03 PM" src="https://github.com/user-attachments/assets/4cca20a5-8ef3-49d6-b653-fc613c7ea660" />


