# Understanding-Cyber-Threats-Exploring-the-Nessus-and-Beyond-scanning-tools.

1. Introduction
In today's digital landscape, cybersecurity threats are constantly evolving, targeting organizations, businesses, and individuals. To mitigate these risks, vulnerability assessment plays a crucial role in identifying and addressing security weaknesses before they can be exploited by attackers.

This project, "Understanding Cyber Threats: Exploring Nessus and Beyond Scanning Tools," focuses on leveraging Nessus, a leading vulnerability scanning tool, to analyze system vulnerabilities. Additionally, we compare Nessus with other scanning tools and explore best practices for proactive cybersecurity.

2. Objectives
The primary goals of this project are:
✅ Understanding cyber threats and vulnerabilities affecting systems, networks, and applications.
✅ Performing hands-on vulnerability scanning using Nessus.
✅ Exploring alternative scanning tools like OpenVAS, Qualys, and Nexpose.
✅ Comparing the effectiveness and detection capabilities of different vulnerability assessment tools.
✅ Providing best practices for addressing vulnerabilities and improving security posture.

3. Tools & Technologies Used
🔹 Kali Linux – Security testing platform
🔹 Nessus – Vulnerability scanning tool
🔹 Metasploitable 2 – A deliberately vulnerable virtual machine
🔹 VirtualBox – Virtualization platform to run Metasploitable 2
🔹 Metasploit Framework – For exploitation and testing security flaws

4. Project Execution
🔹 Step 1: Setting Up the Environment
Installed Kali Linux and ensured it was updated.
Installed Nessus on Kali Linux and activated it.
Downloaded and configured Metasploitable 2 in VirtualBox.
Found the IP address of Metasploitable 2 (ifconfig).
🔹 Step 2: Performing Vulnerability Assessment with Nessus
Started Nessus service (sudo systemctl start nessusd).
Accessed Nessus via https://localhost:8834.
Created a new scan in Nessus:
Scan Type: Basic Network Scan
Target: Metasploitable 2 IP (192.168.72.129)
Ran the scan and analyzed vulnerabilities:
Critical & High vulnerabilities were identified.
Risk ratings, exploitability, and mitigation recommendations were reviewed.
🔹 Step 3: Exploiting Vulnerabilities Using Metasploit
Used Metasploit Framework to test identified vulnerabilities.
Successfully exploited known vulnerabilities (e.g., misconfigured services).
Demonstrated privilege escalation and remote code execution.
🔹 Step 4: Comparing Nessus with Other Tools
Compared Nessus results with OpenVAS, Qualys, and Nexpose.
Analyzed differences in scanning speed, accuracy, and reporting features.
5. Results & Findings
📌 Key vulnerabilities found:

Outdated software versions (e.g., Apache, MySQL, OpenSSH).
Default credentials (e.g., msfadmin/msfadmin).
Open ports & misconfigured services (FTP, Telnet, SMB).
Privilege escalation possibilities.
📌 Comparison of Nessus vs. OpenVAS, Qualys, Nexpose:

Tool	Strengths	Weaknesses
Nessus	Highly detailed reports, strong vulnerability detection	Paid version required for advanced features
OpenVAS	Free & open-source, good for penetration testing	Slower scan times
Qualys	Cloud-based, strong compliance reports	Requires enterprise subscription
Nexpose	Integrated with Metasploit, real-time threat updates	Requires significant system resources
6. Conclusion & Best Practices
✅ Regularly update and patch systems to mitigate vulnerabilities.
✅ Disable unnecessary services and use strong authentication methods.
✅ Conduct regular vulnerability scans using Nessus or alternative tools.
✅ Implement firewalls and intrusion detection systems (IDS).
✅ Follow cyber hygiene best practices to reduce security risks.

7. Future Enhancements
🔹 Automating vulnerability scanning with cron jobs.
🔹 Integrating Nessus with SIEM tools for real-time threat monitoring.
🔹 Using AI-driven threat intelligence for proactive security measures.

8. References
Nessus Documentation: https://www.tenable.com/products/nessus
Metasploit Framework: https://www.metasploit.com/
Cybersecurity Best Practices: https://www.cisa.gov/cybersecurity
