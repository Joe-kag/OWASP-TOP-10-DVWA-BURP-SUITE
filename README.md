# OWASP-TOP-10-DVWA-BURP-SUITE

Application Security
🛡️ Tackling the OWASP Top 10 – Hands-On Exploitation & Mitigation
Overview
This project is a hands-on exploration of the OWASP Top 10, aimed at understanding how critical web application vulnerabilities are discovered, exploited, and mitigated in real-world scenarios. Using tools like Burp Suite and vulnerable platforms such as Damn Vulnerable Web Application (DVWA), I reproduced common security flaws to enhance my offensive and defensive security skills.

🔍 Objective: Strengthen my practical understanding of web application vulnerabilities to support secure application design, testing, and remediation strategies.

🔐 Vulnerabilities Explored
1. # SQL Injection (A03:2021)
Simulated classic and blind SQL injection attacks

Extracted sensitive data from poorly secured database queries

Observed the importance of input validation and parameterized queries

![W4](https://github.com/user-attachments/assets/19a0aa97-6102-4761-b982-8d280c7347a0)


2. # Cross-Site Scripting – XSS (A07:2021)
Performed reflected and stored XSS attacks

Injected malicious JavaScript into vulnerable inputs

Highlighted the importance of output encoding and CSP (Content Security Policy)

3. # Broken Access Control (A01:2021)
Bypassed access restrictions using direct URL manipulation and insecure ID references

Tested for privilege escalation

Demonstrated the need for proper authorization logic at every access point

![w2](https://github.com/user-attachments/assets/2fa9af18-9398-4ed8-9ed6-db6d34ba5c98)


4. # Identification and Authentication Failures (A07:2021)
Executed brute force login attempts using Burp Intruder

Assessed weak password policies and insecure session management

Emphasized multi-factor authentication and rate-limiting mechanisms

![w1](https://github.com/user-attachments/assets/8da7d398-7dc2-4fb9-b42a-75d3953b2535)


5. # Server-Side Request Forgery – SSRF (A10:2021)
Simulated unauthorized internal requests via SSRF vulnerabilities

Demonstrated how SSRF can be used for lateral movement within cloud environments

Reinforced the importance of input validation and metadata protection

🛠️ #Tools & Platforms Used
Burp Suite Community Edition – Web proxy for intercepting and modifying HTTP requests

DVWA (Damn Vulnerable Web Application) – Intentionally insecure PHP/MySQL app for testing

![W4](https://github.com/user-attachments/assets/fced3769-eb49-4ae8-aa4f-670ddbb3bc8d)


Kali Linux – Penetration testing environment

Firefox Developer Edition – Manual testing and script injection

🎯 Key Takeaways
Real-world exploitation highlights the practical dangers of insecure code.

Effective defense requires secure design, strong access control, and proactive validation.

Tools like Burp Suite are essential for both offensive testing and defensive development.

📌 Next Steps
Expand coverage to additional OWASP Top 10 vulnerabilities (e.g., Insecure Design, Security Misconfiguration)

Implement secure coding fixes and showcase mitigations alongside each exploit

Integrate automated scanning tools like OWASP ZAP and Nikto

![w](https://github.com/user-attachments/assets/b7efec51-29af-4dc6-b476-eae4bd33a721)


📚 References
OWASP Top 10 - Official Site

DVWA GitHub

Burp Suite
