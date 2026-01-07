# Vulnerable Web Application Security Lab Report

## 1. Objective
To identify and understand common web application vulnerabilities
using a deliberately vulnerable application in a controlled environment.

---

## 2. Tools Used
- Kali Linux
- Damn Vulnerable Web Application (DVWA)
- Web Browser
- Linux Terminal

---

## 3. Environment Setup
- Attacker Machine: Kali Linux (Virtual Machine)
- Target Application: DVWA
- Network Type: Isolated / Host-only network

---

## 4. Testing Methodology
The following vulnerabilities were explored:
- SQL Injection
- Cross-Site Scripting (XSS)
- Command Injection

Testing was conducted following basic ethical hacking methodology:
reconnaissance, testing, documentation.

---

## 5. Findings Summary
- SQL Injection vulnerabilities allowed database interaction
- XSS vulnerabilities allowed script execution in the browser
- Command injection allowed limited command execution

---

## 6. Risk & Impact
If exploited in real systems, these vulnerabilities could lead to:
- Data leakage
- Account compromise
- Server control

---

## 7. Mitigation Recommendations
- Input validation and sanitization
- Use of prepared statements
- Web application firewalls
- Secure coding practices

---

## 8. Lessons Learned
- OWASP Top 10 vulnerabilities are common in insecure apps
- Testing must always be done legally and ethically
- Proper documentation is critical in cybersecurity work
