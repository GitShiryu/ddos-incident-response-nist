# DDoS Incident Response: NIST CSF Framework 🛡️📊

![Google Cybersecurity](https://img.shields.io/badge/Google-Cybersecurity_Professional-4285F4?style=for-the-badge&logo=google&logoColor=white)
![NIST CSF](https://img.shields.io/badge/Framework-NIST_CSF-blue?style=for-the-badge)
![Incident Response](https://img.shields.io/badge/Security-Incident_Response-red?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

---

## 🚀 Project Overview

This repository contains a comprehensive **Incident Response Report** based on a simulated ICMP flood DDoS attack. The analysis follows the **NIST Cybersecurity Framework (CSF)**, detailing every stage from identification to recovery and post-incident lessons learned. 

Developed as part of the **Google Cybersecurity Professional Certificate**, this project demonstrates the ability to translate technical network disruptions into professional business-impact reports.

## 🔍 Case Analysis: ICMP Flood Attack

The scenario involved a critical network disruption where services were offline for 2 hours.
* **Vector:** Distributed ICMP Flood.
* **Impact:** Estimated 5-digit financial loss (aligned with global benchmarks like the IBM Cost of a Data Breach Report).
* **Status:** Successfully Mitigated & Documented.

## 🛠️ NIST CSF Alignment

| Function | Actions Taken |
| :--- | :--- |
| **Identify** | Analyzed network traffic patterns and identified high-volume ICMP requests. |
| **Protect** | Implemented rate limiting and updated firewall rules to filter malicious traffic. |
| **Detect** | Configured IDS/IPS alerts for rapid detection of similar flood patterns. |
| **Respond** | Executed the incident response plan, isolating affected segments and blocking IPs. |
| **Recover** | Restored services within the recovery window and verified system integrity. |

---

## 📊 Key Performance Indicators (KPIs)

To improve future resilience, the following metrics were established:
* **MTTD (Mean Time to Detect):** Target established at $< 5$ minutes.
* **RTO (Recovery Time Objective):** Target established at $1$ hour for critical services.

## 📄 Deliverables
* **Detailed Technical Report:** Comprehensive PDF covering the incident lifecycle.
* **Mitigation Strategies:** Recommendations for network hardening and DDoS prevention.

---

## 🎓 About the Author

Developed by **Eli Rômulo (GitShiryu)** during specialized training in Cybersecurity. This project reflects the commitment to industry-standard documentation and strategic incident management.

---
**Note:** This is an educational project following industry-best practices for professional portfolio building.
