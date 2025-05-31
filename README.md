# SeaScope IR Playbook ♻️🔥 – Securing Heat Waste SCADA Systems

A cybersecurity playbook developed to protect **waste heat recovery SCADA infrastructure**. This capstone project is aligned with industry standards like **NIST 800-82**, **IEC 62443**, and **OWASP IoT**. It includes policies, architecture, and technical implementations to secure industrial control systems (ICS).

---

## 🧠 Project Overview

**SeaScope Technologies** focuses on industrial-scale **waste heat recovery systems**. This playbook delivers:

- 🔐 Network segmentation & Zero Trust architecture
- 🛡️ IDS/IPS rule sets for threat detection (Zeek, Suricata)
- 📶 VPN, ACLs, VLANs for secure remote access
- 📊 SIEM integration for anomaly detection (Splunk, QRadar)
- 🚨 Insider threat monitoring and access controls
- 🔁 Business Continuity & Disaster Recovery playbook

---

## 📄 View the Full Playbook (PDF)

> 📄 [View the Full SeaScope IR Playbook (Google Drive Preview) ↗](https://drive.google.com/file/d/1W_Q-Tw16sB3yZ0420-M1wYpxZ7akDjRO/view?usp=sharing)

Contains detailed:
- Network design & segmentation diagrams
- Firewall and ACL rule logic
- Encryption & key management policy
- IoT device security and OWASP Top 10 alignment
- Disaster recovery testing & ransomware response

---

## 🧰 Key Technologies Used

| Category               | Tools & Techniques                            |
|------------------------|-----------------------------------------------|
| Network Monitoring     | Wireshark · Zeek · Suricata                   |
| SIEM & Alerting        | Splunk · IBM QRadar · UEBA                    |
| Access Control         | ACLs · RBAC · MFA · VLANs                     |
| Communication Security | IPsec VPN · TLS 1.3 · DPI                     |
| Frameworks & Standards | NIST 800-82 · IEC 62443 · OWASP IoT Top 10    |

---

## 🧱 Architecture Overview

- 🔹 **Zones:** Corporate IT, Industrial SCADA, DMZ, SIEM/SOC
- 🔹 **Protocols Secured:** Modbus, MQTT, OPC UA
- 🔹 **VLAN Segmentation** to isolate sensors, edge devices, and SCADA
- 🔹 **Zero Trust Enforcement** through NAC, MFA, and least privilege


