# ICS344 Course Project – Security Exploitation and Defense

## Group Details

- **Group Number**: 3
- **Members**:
  - AHMED AL MUGHIRAH – ID: 202018480 (33%) 
  - ESSA  ALMUTAWA  – ID: 201959470  (33%)
  - ABDULRAHEEM ALSIBYANI – ID: 202176530  (33%)

---



## 🧩 Phase Overview


### 🔹 Phase 1: Setup and Compromise
- Configured Kali Linux as the attacker and Metasploitable3 as the victim
- Verified network connection and scanned victim using Nmap
- Discovered open SSH port (22) with weak default credentials
- Exploited the SSH service using Metasploit brute-force module
- Successfully logged in with credentials `vagrant:vagrant`
- Developed a custom Python script using Paramiko to automate the attack

---

### 🔹 Phase 2: SIEM Log Analysis
- Generated SSH login logs on Kali Linux and transferred them to Windows
- Installed and configured Splunk for log analysis
- Enabled auto-mount and indexing of log folder
- Used Splunk search and visualization tools to analyze and display the attack timeline

---

### 🔹 Phase 3: Defense and Validation
- Identified weak SSH credentials as the main vulnerability
- Installed and configured **Fail2Ban** on Metasploitable3 to block brute-force attempts
- Re-ran the attack and confirmed the attacker’s IP was banned
- Verified defense effectiveness through Splunk logs and screenshots

---

