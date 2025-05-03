# ICS344 Course Project – Security Exploitation and Defense

## Group Details

- **Group Number**: 2
- **Members**:
  - AHMED AL MUGHIRAH– ID: 202018480
  - ESSA  ALMUTAWA  – ID: 201959470

---

## 📁 Repository Structure

```
ics344-project/
│
├── Phase1/
│   ├── setup/                  # IP and service detection
│   ├── metasploit/             # Metasploit SMB attack
│   ├── custom-script/          # Simulated FTP attack via Python
│   └── notes.md
│
├── Phase2/
│   ├── siem-setup/             # Simulated SIEM log integration
│   ├── analysis/               # Visualization and attack log analysis
│   └── notes.md
│
├── Phase3/
│   ├── defense/                # Defense implementation (e.g., disabling SMBv1)
│   ├── results/                # Before vs After comparison screenshots
│   └── notes.md
```

---

## 🧩 Phase Overview

### 🔹 Phase 1: Setup and Compromise
- Setup Kali Linux as attacker and Windows 7 as victim
- Conducted Nmap scan to identify open ports
- Exploited SMB vulnerability (MS17-010) using Metasploit
- Created and executed a custom Python script simulating an FTP backdoor

### 🔹 Phase 2: SIEM Log Analysis
- Simulated SIEM setup for log integration
- Presented attack logs and timeline
- Compared logs from both victim and attacker perspectives

### 🔹 Phase 3: Defense and Validation
- Disabled SMBv1 and simulated MS17-010 patch application
- Re-ran Metasploit exploit; verified it no longer succeeded
- Provided screenshots for before-and-after comparison

---

## 📌 Notes
- All configurations, scripts, and screenshots are organized per phase
- Each phase includes a `notes.md` file explaining the approach, tools, and results
- Simulations were used where realistic setup wasn’t possible due to resource constraints



