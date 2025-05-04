# ICS344 Course Project – Security Exploitation and Defense

## Group Details

- **Group Number**: 2
- **Members**:
  - AHMED AL MUGHIRAH– ID: 202018480 (50%) 
  - ESSA  ALMUTAWA  – ID: 201959470  (50%)

---

## 📁 Repository Structure

```
ics344-project/
│
├── Phase1/
│   ├── custom-script/          # Simulated FTP attack via Python
│   └── Report.pdf
│
├── Phase2/
│   └── Report.pdf
│
├── Phase3/
│   └── Report.pdf
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

