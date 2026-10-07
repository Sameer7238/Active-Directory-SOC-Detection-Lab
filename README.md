# 🛡️ Active Directory SOC Detection Lab

A hands-on cybersecurity lab designed to simulate common attacks against an **Active Directory environment** and detect, investigate, and respond to suspicious activity using **Wazuh SIEM** and native Windows security logs.

The project is focused on developing practical **SOC analyst skills**, including log analysis, detection engineering, incident investigation, MITRE ATT&CK mapping, and security hardening.

---

## 🎯 Project Objectives

-🎯 Objectives
- Build an Active Directory security lab.
- Integrate Windows systems with Wazuh SIEM.
- Simulate common AD attacks.
- Detect and investigate suspicious activity.
- Analyze Windows security logs.
- Map attacks to MITRE ATT&CK.
- Develop detection and response skills.
---

## Lab Architecture
![alt text](<Screenshots/AD Lab Structure.png>)

---

## 💻 Lab Environment

| Component | Role |
|---|---|
| Kali Linux | Attack simulation |
| Windows Server | Active Directory Domain Controller|
| Windows 11 | Domain-joined endpoint |
| Wazuh | SIEM, log collection and detection |

---

## 🛠️ Technologies Used

- Active Directory
- Windows Server
- Windows 11
- Kali Linux
- Wazuh SIEM
- Windows Event Logs
- MITRE ATT&CK


---

## 🔎 Detection & Attack Scenarios

The lab will progressively simulate and investigate different attack techniques commonly associated with Active Directory environments.

| # | Attacks | 
|---|---|
| 1 | Brute Force Authentication |
| 2 | Active Directory Account Deletion |
| 3 | Active Directory Account Creation |
| 4 | Pass-the-Hash | 

---



## 📊 Windows Event Monitoring

The project uses native Windows Security Event Logs as the primary telemetry source.

Some important events include:

| Event ID | Description |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4634 | Logoff |
| 4647 | User initiated logoff |
| 4720 | User account created |
| 4722 | User account enabled |
| 4725 | User account disabled |
| 4726 | User account deleted |
---

## 🧩 MITRE ATT&CK Integration

Detected activities are mapped to the **MITRE ATT&CK framework** to understand attacker behavior and improve detection coverage.


## 🔐 Security Hardening

After each attack simulation, defensive recommendations will be documented.


## 📈 Skills Demonstrated

This project demonstrates practical experience with:

- Active Directory
- Windows Security Event Analysis
- SIEM
- Wazuh
- Security Monitoring
- Log Analysis
- MITRE ATT&CK

---


## ⚠️ Disclaimer

This project was developed in an isolated laboratory environment for educational and defensive cybersecurity purposes.

All attack simulations are performed only against systems owned and controlled within the lab environment. No unauthorized systems or networks are targeted.

---

## 👨‍💻 Author

**Sameer Shaik**

Cybersecurity Student | SOC Analyst Learner

Focused on:

**SOC Operations • Threat Detection • Active Directory Security • SIEM • Incident Response**