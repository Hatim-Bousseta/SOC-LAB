# SOC-LAB
A complete SOC lab with Wazuh, ELK, Zeek, pfSense, Snort, TheHive, Cortex, MISP, and Shuffle.

#  Advanced Security Operation Center (SOC) Lab

This lab is a fully functional, open-source-based Security Operation Center (SOC) environment designed for learning, simulation, and hands-on practice in threat detection, investigation, and response.

## 📌 Overview

The project integrates a wide range of tools and platforms to simulate realistic blue team and red team operations. It includes endpoint agents, SIEM components, SOAR, firewall, IDS, threat intel platforms, and attack emulation.

---

##  Architecture Components

### 🔸 Endpoints (Wazuh Agents)
- **Windows Server 2016** – Domain Controller
- **Windows Client**
- **Ubuntu Client**
- **Parrot OS Client** – Linux workstation for diversity

### 🔸 Monitoring & Analysis
- **Wazuh** – Agent management and log analysis
- **ELK Stack (ElasticSearch, Logstash, Kibana)** – Visual dashboard and storage

### 🔸 Network Security
- **pfSense Firewall**
- **Snort IDS** integrated within pfSense
- **Zeek** – Network traffic analysis
- **Custom Zeek detection scripts** – Alert generation based on suspicious patterns

### 🔸 Threat Simulation
- **Kali Linux** – Attacker machine for red team scenarios (penetration testing, malware, brute-force, etc.)

### 🔸 SOAR & Threat Intelligence
- **Shuffle SOAR** – Automation of security workflows
  - Integrated with:
    - **Gmail API** – Alert notifications
    - **VirusTotal API** – File/URL intelligence enrichment
- **TheHive** – Incident response platform
- **Cortex** – Analyzer engine connected to TheHive
- **MISP** – Threat intelligence sharing (feeds and IOCs)

---

## 🔧 Integrations

- **Wazuh Server ⇄ ELK Stack**
- **pfSense ⇄ Snort IDS**
- **Shuffle ⇄ TheHive ⇄ Cortex ⇄ MISP**
- **Zeek ⇄ Wazuh via custom scripts**
- **Shuffle ⇄ Gmail + VirusTotal APIs**

---

## Goals & Use Cases

- Simulate real-world SOC environments
- Practice blue team monitoring and incident response
- Automate threat detection and alerting
- Enrich incidents with threat intel sources
- Test offensive security techniques in a safe environment

---

## Screenshots & Architecture

(Insert diagrams or screenshots here if available)

---

##  Future Improvements

- Add MITRE ATT&CK correlation
- Integrate YARA or Suricata
- Automate IOC ingestion from MISP to Wazuh

---



---

## Author

Built by BOUSSETA HATIM 


