# 🛡️ Defensive Security Intro – TryHackMe

## 📌 Overview
The **Defensive Security Intro** room provides a foundational hands-on experience in blue-team operations.
This module introduces the defender’s mindset, log analysis, incident detection, and basic threat-hunting concepts.

---

## 🎯 Learning Objectives
- Understand the difference between **offensive** and **defensive** approaches.
- Apply **log analysis** techniques to detect malicious activity.
- Use basic **SIEM tooling** to monitor and investigate alerts.
- Recognize common **attack patterns** and map them to detections.
- Develop structured **incident documentation** and reporting skills.

---

## 🛠️ Key Skills Practiced
- Collecting and filtering logs (Windows Event Logs, Linux auth logs, web server logs).
- Investigating suspicious processes and network traffic (e.g., netstat, Sysmon, Zeek/Suricata outputs).
- Identifying Indicators of Compromise (IoCs) and correlating events.
- Querying SIEM dashboards (Kibana/Splunk) and writing simple detection queries (Sigma-style).
- Writing clear **Incident Response** notes and timelines.

---

## 🔎 Walkthrough Summary
- Ingest logs into SIEM and verify data sources.
- Run baseline queries to establish normal behavior.
- Hunt for anomalies (failed logins bursts, unusual parent-child processes, odd outbound connections).
- Pivot on IoCs (hash, domain, IP) and correlate across hosts.
- Document findings, impact, and recommended remediations.

---

## 📸 Evidence & Screenshots
![imag alt](https://github.com/djhdhdgddfgdd/TryHackMe-RedTeam-Docs/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-08-20%20081759.png?raw=true)
![imag alt](https://github.com/djhdhdgddfgdd/TryHackMe-RedTeam-Docs/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-08-22%20070029.png?raw=true)
![imag alt](https://github.com/djhdhdgddfgdd/TryHackMe-RedTeam-Docs/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-08-22%20070052.png?raw=true)
![imag alt](https://github.com/djhdhdgddfgdd/TryHackMe-RedTeam-Docs/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-08-22%20070220.png?raw=true)
![imag alt]()

