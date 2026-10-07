# Lab Setup

## 1. Lab Overview

This lab was created to simulate an enterprise Active Directory environment and monitor security activity using Wazuh SIEM.

The environment consists of a Domain Controller, a Windows client, and a Kali Linux machine used for controlled attack simulations.

## 2. Lab Components

| System | Role |
|---|---|
| Windows Server | Active Directory Domain Controller|
| Windows 11 | Domain-joined endpoint |
| Kali Linux | Attack simulation |
| Wazuh Server | SIEM and security monitoring |


## 3. Active Directory Setup

A Windows Server virtual machine was configured as the Active Directory Domain Controller.

![alt text](Screenshots.md/AD.png)

The following services were configured:

- Active Directory Domain Services (AD DS)
- DNS
- Domain authentication
- Domain users and groups


## 4. Windows 11 Domain Client

A Windows 11 virtual machine was configured as a domain-joined endpoint.

The machine was successfully connected to the Active Directory domain and can authenticate using domain accounts.

![alt text](<Screenshots.md/Windows 11.png>)

## 5. Wazuh SIEM

Wazuh was deployed as the central security monitoring platform.

![alt text](Screenshots.md/Wazuh_server.png)

The Wazuh environment consists of:

- Wazuh Manager
- Wazuh Dashboard
- Wazuh Agent
- Wazuh Indexer


## 6. Attack Simulation

Kali Linux is used as the attack simulation machine.

All attack simulations are performed only against the isolated lab environment.



### Completed

- [x] Windows Server deployed
- [x] Active Directory configured
- [x] Windows 11 deployed
- [x] Windows 11 joined to the domain
- [x] Wazuh Server deployed
- [x] Windows systems connected to Wazuh


