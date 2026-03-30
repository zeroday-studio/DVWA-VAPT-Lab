# 🔐 DVWA Web Application Vulnerability Assessment & Exploitation

## 📌 Overview
This project demonstrates a complete web application penetration testing (VAPT) lab using DVWA. It focuses on identifying, exploiting, and mitigating common web vulnerabilities based on OWASP Top 10.

---

> ⚠️ **Disclaimer**  
This project is created for **educational and ethical purposes only**. All testing was performed in a controlled lab environment using intentionally vulnerable systems (DVWA & Metasploitable2).  
Do NOT attempt these techniques on real systems without proper authorization.

---

## 🎯 Objectives
- Simulate real-world web attacks  
- Identify vulnerabilities  
- Perform exploitation  
- Provide mitigation techniques  

---

## 🧠 Skills Demonstrated
- Web Application Penetration Testing (VAPT)
- OWASP Top 10 Vulnerability Analysis
- Manual Exploitation Techniques
- Burp Suite (Proxy Interception)
- Hydra (Brute Force Attack)
- Linux Command Execution

---

## 🧭 Lab Setup
- Kali Linux (Attacker) – 192.168.10.5  
- Metasploitable2 (Target) – 192.168.10.50  
- DVWA Web Application  

---

## 🔥 Vulnerabilities Covered
- SQL Injection  
- Cross-Site Scripting (XSS)  
- Command Injection  
- Brute Force Attack (Hydra)  
- File Inclusion (LFI)  
- CSRF  
- File Upload (RCE)  

---

## 📁 Repository Contents

- `attacks/` → Detailed attack methodology, exploitation, and mitigation  
- `screenshots/` → Evidence of all vulnerabilities  
- `report/` → Final VAPT report (PDF)                                                                                                                                                                                                                        
---

## ⚔️ Attack Phases

This project follows a structured penetration testing lifecycle divided into three phases:

### 🔹 Phase 1: Methodology (Steps)
Detailed step-by-step procedures used to identify and test vulnerabilities.  

👉 [View Steps](attacks/steps.md)

---

### 🔹 Phase 2: Exploitation
Demonstrates how vulnerabilities were successfully exploited along with their impact.  

👉 [View Exploitation](attacks/exploitation.md)

---

### 🔹 Phase 3: Mitigation
Provides security recommendations and best practices to fix the identified vulnerabilities.  

👉 [View Mitigation](attacks/mitigation.md)

---

## 📸 Sample Evidence

![SQL Injection](screenshots/fig5_sqli_success.png)  
![XSS](screenshots/fig10_xss_reflected_alert.png)  
![RCE](screenshots/fig31_rce_execution.png)  

---

## 📊 Vulnerability Severity

- SQL Injection → Critical  
- XSS → High  
- Command Injection → Critical  
- Brute Force → High  
- LFI → Critical  
- CSRF → Medium  
- File Upload (RCE) → Critical  

---

## 🛡️ Mitigation Overview
- Use input validation and sanitization  
- Implement prepared statements  
- Enable rate limiting and account lockout  
- Use CSRF tokens  
- Validate file uploads  
- Apply Content Security Policy (CSP)  

---

## 📸 Evidence
All screenshots are available in the **screenshots/** folder.

---

## 📑 Report

A detailed VAPT report documenting all identified vulnerabilities, exploitation steps, and mitigation strategies is included.

👉 [View Full Report](report/dvwa_vapt_report.pdf)

---

⭐ If you found this project useful, consider giving it a star!

---

## 👨‍💻 Author
**Rakesh A R**  
Cybersecurity Enthusiast  
🔗 https://www.linkedin.com/in/rakesh-a-r-595517288
