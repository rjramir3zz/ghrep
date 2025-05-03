# 🛠️ GHREP – IT Ops & Maintenance Scripts

This repository contains Standard Operating Procedures (SOPs), PowerShell scripts, and automation tools for IT infrastructure maintenance and operations. Primarily focused on Windows Server, Active Directory, and domain controller health checks.

---

## 📌 Key Contents

- 📝 SOP: Preventive Maintenance for Domain Controllers  
- 🔁 Scripts: Automated health checks, service validation  
- 📊 Output Samples: JSON logs and report formats  
- 🖼️ Diagrams: Architecture references and flowcharts

---

## 📂 Structure

| Folder | Description |
|--------|-------------|
| `/docs` | Markdown SOPs and written instructions |
| `/scripts` | PowerShell or Bash automation scripts |
| `/resources` | Output samples, templates |
| `/assets` | Diagrams, screenshots, visuals |

---

## 🧪 Sample Use Case

Run this script weekly to check AD services:

```powershell
.\check-dc-health.ps1 -Verbose
