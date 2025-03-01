# CS-305---Project-One

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that required a secure software solution to protect sensitive financial data. The company was concerned about security vulnerabilities in its existing system, particularly regarding data breaches, unauthorized access, and weak encryption practices. My task was to identify these security weaknesses, address them, and implement stronger security measures to safeguard their platform.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

One of my key strengths in this project was conducting a thorough vulnerability assessment and implementing secure coding practices to mitigate risks. I effectively identified SQL injection risks, weak password policies, and insufficient access controls, then applied secure authentication, encryption, and input validation techniques.

Coding securely is crucial because cyber threats are constantly evolving, and poorly written code can lead to data breaches, financial losses, and reputational damage. Implementing strong security measures enhances trust, ensures regulatory compliance, and protects the company’s assets and customers.

3. Which part of the vulnerability assessment was challenging or helpful to you?
   
The most challenging aspect of the vulnerability assessment was detecting hidden security flaws, such as privilege escalation exploits, insecure API endpoints, and misconfigured access controls. Identifying these vulnerabilities required an in-depth understanding of system architecture, network security, and penetration testing methodologies. However, this challenge was also a valuable learning experience as it sharpened my skills in analyzing security logs, conducting ethical hacking tests, and applying real-time risk mitigation strategies.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

To enhance security, I implemented multiple layers of protection, including multi-factor authentication (MFA) to strengthen user verification, AES-256 and TLS/SSL encryption to secure sensitive data, role-based access control (RBAC) to restrict system permissions, and input validation to prevent SQL injection and cross-site scripting (XSS) attacks. In the future, I would use penetration testing tools such as OWASP ZAP and Burp Suite for real-time vulnerability detection, static and dynamic code analysis to identify weaknesses in the codebase, and security monitoring tools like SIEM systems to detect and respond to threats proactively. These techniques would allow for early detection of security issues and more effective risk management.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
   
To ensure the functionality and security of the software, I performed unit testing to verify individual components, integration testing to confirm seamless system interactions, and automated security scans using SonarQube to detect potential vulnerabilities. Additionally, I reviewed the codebase with peers, conducted penetration testing, and monitored system behavior under different scenarios to ensure security measures were effective. After refactoring the code, I ran regression tests to verify that previous security fixes remained intact, re-scanned for vulnerabilities, and performed another round of penetration testing to confirm that no new security flaws had been introduced.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
   
Some of the most valuable resources and tools I used in this project included OWASP secure coding guidelines for best practices, Git version control for tracking changes and ensuring secure deployments, and penetration testing tools such as OWASP ZAP, Burp Suite, and Nmap for vulnerability assessments. Additionally, I relied on logging and monitoring techniques to track security events and detect anomalies. These tools and practices will be highly beneficial in future security-focused software development projects by helping me build more resilient, attack-resistant applications.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
   
For future employers, I would present before-and-after security reports showcasing how I identified and resolved vulnerabilities, code samples demonstrating secure coding practices such as encryption, authentication, and validation, and penetration test results highlighting proactive security measures. Additionally, I would share documentation outlining security strategies and compliance measures to illustrate my ability to analyze, enhance, and maintain secure software systems. This project serves as a strong example of my technical skills, security expertise, and problem-solving abilities, which are essential in cybersecurity and software development roles.


