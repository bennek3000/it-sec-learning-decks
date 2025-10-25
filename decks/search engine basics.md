# Search Engine Basics and Cybersecurity Tools

### Card 1
**Q:** Which Google search operator returns results that match an exact phrase?  
**A:** Quotation marks `" "` — they force Google to show only pages containing that precise wording.

---

**Q:** Which Google search operator restricts results to a specific domain or website?  
**A:** `site:` — limits results to a chosen domain.  
**Example:** `site:example.com`

---

**Q:** Which Google operator removes results containing unwanted terms?  
**A:** The minus sign `-` — it excludes specified keywords from the search.

---

**Q:** Which Google operator is used to find a specific type of file, like a PDF or Word document?  
**A:** `filetype:` — filters results by file extension.  
**Example:** `filetype:pdf cybersecurity report`

---

**Q:** What Linux command replaced `netstat` and is used for socket information?  
**A:** `ss` — short for *socket statistics*; it displays active connections and ports.

---

**Q:** What is Shodan, and what can it reveal?  
**A:** A specialized search engine that indexes internet-connected devices and services, such as routers, cameras, and IoT systems.

---

**Q:** What is the main function of Censys?  
**A:** It maps internet-connected assets by continuously scanning IP ranges and analyzing metadata for research and defense.

---

**Q:** How do Shodan and Censys differ in focus?  
**A:** Shodan emphasizes device discovery and accessibility; Censys offers deeper analysis, certificate data, and internet-wide visibility.

---

**Q:** What is VirusTotal designed to do?  
**A:** It scans files and URLs across multiple antivirus engines to identify potential malware and provide detailed reports.

---

**Q:** What does the service “Have I Been Pwned” allow users to check?  
**A:** If their email address or password has been exposed in a known data breach.

---

**Q:** What does CVE stand for in cybersecurity?  
**A:** *Common Vulnerabilities and Exposures* — a catalog of publicly disclosed security flaws in software and hardware.

---

**Q:** Why are CVE identifiers useful?  
**A:** They standardize vulnerability tracking, letting organizations reference and patch specific issues consistently.

---

**Q:** Which Linux command displays built-in manuals for system tools?  
**A:** `man` — shows the manual pages for any available command.  
**Example:**  
```bash
man ip
```

---

**Q:** Why should cybersecurity professionals learn advanced search operators?  
**A:** They improve efficiency in gathering open-source intelligence (OSINT) and identifying relevant information faster.

---

**Q:** Why are tools like Shodan and Censys critical in cyber defense?  
**A:** They help defenders locate exposed assets and vulnerabilities before attackers can exploit them.

---

**Q:** What is the purpose of vulnerability management in an organization?  
**A:** To systematically find, assess, and fix weaknesses to minimize attack surfaces.

# Defensive Security – Study Questions (Rephrased Anki Deck)

---

### Card 1
**Q:** What is the purpose of user cybersecurity awareness training?  
**A:** To teach users how to identify and avoid cyber threats, reducing risks caused by human error or social engineering.

---

### Card 2
**Q:** Why is it important to maintain an up-to-date asset inventory?  
**A:** To ensure all hardware, software, and network components are tracked, managed, and secured properly.

---

### Card 3
**Q:** Why should organizations apply patches and updates regularly?  
**A:** To close known vulnerabilities and reinforce protection against new and existing threats.

---

### Card 4
**Q:** What role do preventive security devices play in cybersecurity?  
**A:** Tools like firewalls and Intrusion Prevention Systems (IPS) block malicious traffic and stop attacks before they cause damage.

---

### Card 5
**Q:** What is the function of logging and monitoring systems?  
**A:** They track network activity to detect intrusions, policy violations, or other suspicious behavior in real time.

---

### Card 6
**Q:** What is a Security Operations Center (SOC)?  
**A:** A team of cybersecurity professionals who continuously monitor and respond to security threats within an organization.

---

### Card 7
**Q:** What are vulnerabilities in the context of a SOC?  
**A:** Weaknesses in systems or configurations that must be patched or mitigated to prevent exploitation.

---

### Card 8
**Q:** What is a policy violation in cybersecurity?  
**A:** When a user breaks established security rules, such as sharing confidential data through unauthorized channels.

---

### Card 9
**Q:** What is considered unauthorized activity in a SOC environment?  
**A:** Any unapproved action—like using stolen credentials—that can compromise system integrity or security.

---

### Card 10
**Q:** What is a network intrusion?  
**A:** Unauthorized access to a network, often through phishing or exploited vulnerabilities, requiring immediate detection and response.

---

### Card 11
**Q:** What is threat intelligence?  
**A:** The process of collecting and analyzing information about cyber threats and adversaries to improve defensive readiness.

---

### Card 12
**Q:** What does “threat-informed defense” mean?  
**A:** A proactive defense approach that uses insights from threat intelligence to anticipate and counter attacker tactics.

---

### Card 13
**Q:** Where does threat intelligence data come from?  
**A:** Both internal sources like logs and alerts, and external ones like security communities or open-source feeds.

---

### Card 14
**Q:** What is the main goal of threat intelligence?  
**A:** To identify potential attackers, predict their actions, and recommend effective mitigation strategies.

---

### Card 15
**Q:** What does DFIR stand for?  
**A:** Digital Forensics and Incident Response.

---

### Card 16
**Q:** What is digital forensics?  
**A:** The scientific process of collecting and analyzing digital evidence to understand what occurred during a cyber incident.

---

### Card 17
**Q:** What does file system analysis involve?  
**A:** Examining storage media to recover deleted files, installed software, and user or attacker activity traces.

---

### Card 18
**Q:** What is memory analysis used for?  
**A:** To inspect system RAM and identify running malicious processes that may not exist on disk.

---

### Card 19
**Q:** Why are system logs important in forensics?  
**A:** They provide a timeline of user actions and events, helping investigators trace activity even if partial evidence remains.

---

### Card 20
**Q:** What does analyzing network logs help determine?  
**A:** The source, timing, and method of attacks or unauthorized data transfers.

---

### Card 21
**Q:** What is the purpose of incident response?  
**A:** To detect, contain, and mitigate cyber incidents, reducing their impact and restoring normal operations quickly.

---

### Card 22
**Q:** What qualifies as a cybersecurity incident?  
**A:** Any event that compromises the confidentiality, integrity, or availability of data, such as breaches or malware infections.

---

### Card 23
**Q:** What are the main objectives of incident response?  
**A:** Minimize damage, recover affected systems, and implement improvements to prevent future incidents.

---

### Card 24
**Q:** What are the four primary phases of incident response?  
**A:** Preparation, Detection & Analysis, Containment/Eradication & Recovery, and Post-Incident Review.

---

### Card 25
**Q:** What is malware?  
**A:** Malicious software designed to harm systems, steal data, or gain unauthorized control.

---

### Card 26
**Q:** What is a computer virus?  
**A:** A self-replicating program that attaches to files or software, spreading across systems and damaging data.

---

### Card 27
**Q:** What is a Trojan horse?  
**A:** Malware that masquerades as legitimate software to deceive users and compromise systems.

---

### Card 28
**Q:** What is ransomware?  
**A:** Malicious software that encrypts user files and demands payment to restore access.

---

### Card 29
**Q:** What is malware analysis?  
**A:** The study of malicious code to understand its purpose, behavior, and potential effects on systems.

---

### Card 30
**Q:** What is static analysis in malware research?  
**A:** Examining malware code or binaries without executing them, often through reverse engineering.

---

### Card 31
**Q:** What is dynamic analysis in malware research?  
**A:** Running malware in a sandbox to observe its behavior, such as file changes or network connections.

---

### Card 32
**Q:** What does SIEM stand for?  
**A:** Security Information and Event Management.

---

### Card 33
**Q:** What is the main purpose of a SIEM system?  
**A:** To collect, correlate, and analyze security data from multiple sources for real-time threat detection and response.

---

### Card 34
**Q:** What does SIM represent within SIEM?  
**A:** Security Information Management — focuses on collecting and storing logs for long-term analysis and compliance.

---

### Card 35
**Q:** What does SEM represent within SIEM?  
**A:** Security Event Management — handles real-time monitoring, alert correlation, and incident detection.

---

### Card 36
**Q:** What are the key benefits of using a SIEM solution?  
**A:** Centralized visibility, automated alerting, quicker detection, and improved investigation and response capabilities.

---

### Card 37
**Q:** Name some common SIEM platforms used in organizations.  
**A:** Splunk, IBM QRadar, and Microsoft Sentinel.

---

### Card 38
**Q:** Which team is responsible for defensive security operations?  
**A:** The Blue Team.

---

### Card 39
**Q:** What should a team do after resolving a cybersecurity incident?  
**A:** Conduct a review, document lessons learned, and update security processes to prevent recurrence.

---

*End of deck.*
