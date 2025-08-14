# 🛡️ Task 1 – Web Application Security Testing

## 📌 Overview
This project was completed as part of my **Cybersecurity Internship with Future Interns**.  
The goal was to perform **web application vulnerability assessment** on a test platform using **OWASP standards**, simulating a real-world client security test.

Target Application: **DVWA (Damn Vulnerable Web Application)**

---

## 🎯 Objectives
- Identify common web application vulnerabilities
- Map findings to the **OWASP Top 10** security risks
- Practice using professional penetration testing tools
- Document vulnerabilities with impact analysis and remediation steps

---

## 🛠 Tools Used
- **OWASP ZAP** – Automated vulnerability scanning
- **Burp Suite (Community Edition)** – Manual interception and testing
- **DVWA** – Intentionally vulnerable web application for testing

---

## 🔍 Vulnerabilities Tested
1. **SQL Injection (A03:2021)**
2. **Cross-Site Scripting (XSS) (A07:2021)**
3. **Cross-Site Request Forgery (CSRF) (A05:2021)**

---

## 📑 Report Summary
| Vulnerability       | OWASP Category | Impact | Mitigation |
|---------------------|---------------|--------|------------|
| SQL Injection       | A03:2021      | High   | Use prepared statements & input validation |
| Cross-Site Scripting| A07:2021      | High   | Encode output & sanitize inputs            |
| CSRF                | A05:2021      | Medium | Implement CSRF tokens & same-site cookies  |

---

## 📂 Deliverables
- **Security Assessment Report (PDF)**  
  Includes findings, screenshots, risk ratings, and recommendations.
- **OWASP Top 10 Mapping Table**
- **Testing Screenshots** (evidence of vulnerabilities)

---

## 📖 How to Reproduce
1. **Set up DVWA** locally or via Docker:
   ```bash
   docker run --rm -it -p 80:80 vulnerables/web-dvwa
