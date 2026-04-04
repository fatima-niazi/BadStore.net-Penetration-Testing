# 🔐 BadStore.net Penetration Testing Report

## 📌 Overview
This repository contains a full **Web Application Penetration Test Report** conducted on the **BadStore.net** application as part of the **CSEC2003 — Web Application Security Assessment**.

The assessment simulates a real-world attack scenario, identifying vulnerabilities and demonstrating how they can be exploited to compromise sensitive data and systems.

---

## 🎯 Objectives
- Perform a structured penetration test following industry standards  
- Identify and exploit web application vulnerabilities  
- Assess the impact of security flaws on business operations  
- Provide actionable remediation recommendations  

---

## 🧪 Methodology
The assessment follows the **OWASP Web Security Testing Guide (WSTG)** framework:

1. Passive Reconnaissance  
2. Active Reconnaissance  
3. Vulnerability Analysis  
4. Exploitation  
5. Post-Exploitation  

---

## 🛠️ Tools Used
- Kali Linux  
- OWASP ZAP  
- Nmap  
- Nikto  
- Dirb  
- WhatWeb  
- cURL  

---

## 🚨 Key Findings

### 🔴 Critical Vulnerabilities
- **SQL Injection**
  - Authentication bypass  
  - Full database extraction (emails, hashes, roles)

- **Unauthenticated Admin Portal**
  - Full user management access without login  

---

### 🟠 High Severity
- **Stored Cross-Site Scripting (XSS)**
  - Session hijacking via guestbook  

---

### 🟡 Medium Severity
- Multiple Apache CVEs:
  - CVE-2001-1556 (Path Disclosure)  
  - CVE-2005-3352 (Referer XSS)  
  - CVE-2006-3918 (Expect Header XSS)  
  - CVE-2007-5000  
  - CVE-2007-6388  

- Directory Indexing Enabled  
- Sensitive Information Disclosure  

---

### 🟢 Low Severity
- Missing Security Headers  
- HTTP TRACE Method Enabled  

---

## 🔗 Attack Chain Demonstrated

- SQL Injection → Extract supplier data  
- OSINT → Identify targets & roles  
- XSS → Session hijacking  
- Final Stage → Targeted phishing attack  

---

## 📄 Report
The full penetration testing report is available in this repository.

---

## 👩‍💻 Author
**Bint e Fatima Niazi**  
- LinkedIn: https://www.linkedin.com/in/bint-e-fatima-niazi/  
- GitHub: https://github.com/fatima-niazi  

---

## ⚠️ Disclaimer
This project was conducted in a **controlled lab environment** for educational purposes only.  
No real systems were harmed.

---

## ⭐ If you found this useful
Feel free to ⭐ star the repo or connect with me on LinkedIn!
