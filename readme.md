# 🛡️ PowerShell Threat Hunting (Event ID 4104)

## 🎯 Objective
Detect suspicious PowerShell activity on a Windows system using native logs (Event ID 4104).

---

## 🧠 What is Event ID 4104?
PowerShell logs this event when a command is executed via a script or command line. It helps detect:
- Obfuscated commands
- Encoded payloads (like base64)
- Suspicious PowerShell usage by attackers

---

## 🔍 What I Did
- Enabled **PowerShell logging**
- Opened **Event Viewer**
- Navigated to:  
  `Applications and Services Logs > Microsoft > Windows > PowerShell > Operational`
- Found and analyzed event ID **4104**
- Captured the suspicious command for investigation

---

## 📸 Screenshot

| Suspicious PowerShell Command |
|------------------------------|
| ![01](screenshots/01-powershell-suspicious-command.png) |

---

## 📌 MITRE ATT&CK Mapping
| Technique Name     | ID         |
|--------------------|------------|
| PowerShell          | T1059.001  |

---

## ✅ Outcome
Successfully identified PowerShell command activity using event logs. This forms the basis of many threat-hunting investigations in real SOC environments.

---

