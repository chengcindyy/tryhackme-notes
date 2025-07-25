# 🧠 Defensive Security Intro
🗓️ Date: 2025-07-24
🔗 Room URL: https://tryhackme.com/room/defensivesecurityintro
🏷️ Tags: \[Blue Team], \[Defensive Security], \[Beginner]

---

## 🧭 Overview

A beginner-friendly room to introduce key concepts in defensive security.
This room focuses on learning how to monitor systems, detect threats through logs, and understand the structure of a security operations team.

>  這題主要介紹如何從日誌中發現異常、封鎖惡意 IP、認識藍隊職能與常見工具。

---

## 🛠 Tools & Concepts and Commands Used

## 🛠 Tools & Concepts Used

| Tool / Concept           | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Log Analysis (simulated SIEM) | Used to review logs and detect suspicious IP addresses  <br>💬 模擬 SIEM 介面查找惡意連線紀錄 |
| Alerting / Detection     | Acted upon suspicious activity by reporting and blocking malicious IPs  <br>💬 根據觀察行為封鎖威脅來源 |
| IP Reputation Lookup     | Checked if incoming IPs were malicious using lookup tools  <br>💬 查詢外部 IP 是否為惡意來源 |
| SOC Workflow Simulation  | Followed a simplified detection-to-response process  <br>💬 模擬分析師偵測 → 回報 → 阻擋的流程 |


---

## 🔍 Key Observations / What I Learned

- [x] **Defensive Security Responsibilities (e.g., SOC Analyst, Threat Hunter)**
  ➤ Includes raising user awareness, applying patches, setting up firewalls/IPS, and enabling log monitoring.
  💬 包含：提升安全意識、修補系統、部署防火牆與設定監控工具

- [x] **Key Blue Team Areas**
  ➤ SOC (Security Operations Center): Team responsible for real-time threat detection and response.
  ➤ DFIR (Digital Forensics and Incident Response): Scientific investigation of cyber events.
  ➤ Malware Analysis: Investigating and reverse-engineering malicious software.
  💬 SOC 是實時偵測與回應中心；DFIR 進行數位鑑識；Malware Analysis 則分析病毒與惡意程式

- [x] **Basic SIEM Use Case in this Room**
  ➤ Used IP lookup to detect a malicious connection attempt.
  ➤ Once confirmed, escalated to SOC lead and blocked the IP.
  ➤ This simulates a real-world analyst's task flow.
  💬 在實作中觀察 log，找出可疑 IP，回報後立即封鎖，這是 SOC 常見任務流程的簡化版

---

### Note:

In this room, I learned how to simulate an analyst's role by identifying a malicious IP through logs and taking action to block it. It also introduced key areas like SOC and DFIR."

> 本題模擬 SOC 分析師的任務流程，包括觀察連線日誌、發現惡意 IP 並通知主管後封鎖該來源。同時也學習到藍隊中重要的三個領域：SOC、DFIR 與 Malware Analysis。

---

## ⚠ Disclaimer

These notes are for personal learning purposes only. No answers or flags are shared. All tasks are completed by me, and all observations are based on legal, sandboxed exercises.
