# 🏢 Enterprise Active Directory Home Lab

<p align="center">

![VMware](https://img.shields.io/badge/VMware_Workstation-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server_2022-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Windows 10](https://img.shields.io/badge/Windows_10-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server_24.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic_Stack-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)

</p>

---

# 📖 Project Overview

This project documents the design and implementation of a small enterprise Active Directory environment built using VMware Workstation Pro.

The environment simulates a corporate network consisting of:

- Windows Server 2022 Domain Controller
- Windows 10 Enterprise Workstation
- Ubuntu Server running the Elastic Stack
- Kali Linux attacker machine

The purpose of this lab is to create a realistic enterprise infrastructure that serves as the foundation for future Security Operations Center (SOC) projects, including:

- SIEM deployment
- Endpoint telemetry
- Attack simulations
- Threat hunting
- Detection engineering
- Incident response investigations

---

# 🎯 Project Objectives

- Build a Windows Active Directory Domain.
- Configure enterprise DNS services.
- Configure static IP addressing.
- Join Windows workstations to the domain.
- Validate domain authentication.
- Build reusable infrastructure for future SOC projects.

---

# 🏗️ Lab Architecture

> **Network Diagram**

```
(Add your diagram here later)
```

---

> **VMware Overview**

```
(Add VMware screenshot here)
```

---

# 💻 Lab Environment

| Virtual Machine | Purpose | Operating System |
|-----------------|----------|------------------|
| DC-01 | Domain Controller | Windows Server 2022 |
| WKSTN-01 | Domain Workstation | Windows 10 Pro |
| SIEM-01 | SIEM Server | Ubuntu Server 24.04 |
| KALI-01 | Attack Machine | Kali Linux Rolling |

---

# ⚙️ Technologies Used

| Category | Technology |
|----------|------------|
| Hypervisor | VMware Workstation Pro 26 |
| Directory Service | Active Directory Domain Services |
| DNS | Windows DNS |
| Operating Systems | Windows Server 2022, Windows 10, Ubuntu Server, Kali Linux |
| SIEM | Elastic Stack |
| Virtual Networking | VMware Virtual Network |

---

# 🌐 Network Topology

| Host | IP Address | Role |
|------|------------|------|
| DC-01 | 192.168.42.10 | Domain Controller |
| WKSTN-01 | 192.168.42.20 | Domain Workstation |
| SIEM-01 | 192.168.42.30 | SIEM |
| KALI-01 | 192.168.42.40 | Attacker |

---

# 🔧 Implementation

## Active Directory

(Add screenshots)

---

## DNS

(Add screenshots)

---

## Domain Join

(Add screenshots)

---

# ✅ Validation

- Ping tests
- nslookup
- whoami
- Domain authentication

(Add screenshots)

---

# 📸 Project Screenshots

(Add screenshots)

---

# 🚧 Challenges Encountered

Examples:

- DNS configuration
- VMware networking
- Static IP configuration
- Domain join troubleshooting

---

# 📚 Lessons Learned

- Understood how Active Directory depends on DNS.
- Learned enterprise IP addressing.
- Improved troubleshooting skills.
- Built a reusable enterprise environment.

---

# 🛠️ Skills Demonstrated

- Active Directory Administration
- DNS Configuration
- Windows Server Administration
- VMware Virtualization
- Enterprise Networking
- Windows Client Administration
- Linux Administration
- Elastic Stack Deployment
- Documentation

---

# 🚀 Next Steps

This lab serves as the foundation for the following projects:

- SIEM Deployment
- Endpoint Telemetry
- Attack Simulation
- Threat Hunting
- Detection Engineering
- Incident Response

