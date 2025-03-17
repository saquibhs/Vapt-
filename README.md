 🔒 VAPT Report: Demoblaze.com (Security Testing Project)

📜 About This Project

This repository contains a **Vulnerability Assessment and Penetration Testing (VAPT) report** for **Demoblaze.com**, a publicly available demo e-commerce platform. The project focuses on identifying security flaws following the **OWASP Top 10 2021 guidelines**. This report is prepared for **educational and learning purposes**, showcasing real-world VAPT methodologies.



 🌐 About Demoblaze.com

[Demoblaze](https://dev.demoblaze.com/) is a **demo online shopping web application** designed for practicing web application development and security testing. It simulates real-world e-commerce functionality, including:

- User Registration & Login
- Product Listings and Detail Pages
- Shopping Cart & Checkout
- Order Placement System

This site is widely used for **learning web application security**, including **OWASP Top 10 vulnerabilities**.



🚀 **Project Goals**

- Perform comprehensive **manual and automated penetration testing** on Demoblaze.
- Identify and report vulnerabilities in line with **OWASP Top 10 2021**.
- Provide **Proof of Concepts (PoCs)**, impact analysis, and **remediation recommendations**.
- Demonstrate VAPT skills for **portfolio, learning, and showcase**.



 🔍 **Identified Vulnerabilities**

The following vulnerabilities were identified during the security assessment:

1. **Hardcoded Sensitive Information in Source Code (A02:2021 - Cryptographic Failures)**
2. **Outdated JavaScript Libraries - Client-side Vulnerability (A06:2021 - Vulnerable and Outdated Components)**
3. **Session Fixation (A01:2021 - Broken Access Control)**
4. **SQL Injection in Login Page (A03:2021 - Injection)**
   


 ⚙️ **Tools Used**

- **Burp Suite Community Edition** (Manual testing, intercept requests)
- **OWASP ZAP** (Scanning)
- **Browser DevTools** (Source code analysis)
- **SQLMap** (Automated SQL Injection testing)
- **Custom manual payloads and scripts**


## 📂 **Repository Structure**
VAPT-Demoblaze/
│
├── README.md                    # 📄 Project overview and description
├── VAPT_Report_DemoBlaze.docx   # 📝 Full detailed VAPT report (DOCX format)
├── VAPT_Report_DemoBlaze.pdf    # 📄 (Optional) PDF version of the VAPT report for easy viewing
├── artifacts/                   # 📸 Proof of Concept (PoC) screenshots and evidence
│   ├── csrf_order_place.png     # CSRF attack evidence on order placement
│   ├── session_fixation.png     # Session fixation PoC screenshot
│   ├── sql_injection_login.png # SQL Injection in login page PoC
│  
└

