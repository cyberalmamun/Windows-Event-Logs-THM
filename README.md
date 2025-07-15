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

## 📁 Repo Structure

