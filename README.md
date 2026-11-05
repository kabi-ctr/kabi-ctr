# Kabir Poudel

Computer engineer in Helsinki, Finland, working on security analysis, testing and data.
MSc student in AI & Data Engineering at the University of Vaasa (2025–2027).

[LinkedIn](https://www.linkedin.com/in/kabir-poudel-842a471b7) · [Email](mailto:poudelkabir31@gmail.com) · English (C1) · Finnish (A2) · Nepali (native)

**Open to:** junior, intern/trainee and part-time roles in security operations, application security, data engineering, or test & verification. Finland (on-site or hybrid) or remote within the EU.

---

## Projects

**[log_analyzer](https://github.com/kabi-ctr/log_analyzer)**: Python CLI for OpenSSH authentication logs
- Parses `sshd` login events and flags any IP with N failed logins inside a sliding time window. The rule is set in YAML (default: 5 failures in 10 minutes).
- Writes a Markdown report with suggested `nftables` / `iptables` block rules. Nothing is executed automatically.
- pandas · pytest unit tests · ruff lint · GitHub Actions CI on every push

**[security_analyst_training](https://github.com/kabi-ctr/security_analyst_training)**: SOC lab cases, written up as analyst reports
- [Phishing IOC analysis](https://github.com/kabi-ctr/security_analyst_training/blob/main/threat_intelligence/IOC_analysis.md) (LetsDefend SOC282): detonated the attachment in ANY.RUN, checked hashes and domains in VirusTotal, extracted hashes, IPs and domains for blocking.
- [Phishing incident report](https://github.com/kabi-ctr/security_analyst_training/blob/main/incident-response/phishing-incident-report.md) (LetsDefend SOC146) and an [incident response playbook](https://github.com/kabi-ctr/security_analyst_training/blob/main/incident-response/incident-response-playbook.md).
- [Spam text classifier](https://github.com/kabi-ctr/security_analyst_training/tree/main/threat-detection-ml/phishing_email_detector): TF-IDF features; compared logistic regression, naive Bayes, SVM and a decision tree on the SMS Spam Collection (5,572 messages). Naive Bayes reached 97.3% accuracy.
- Notes on MITRE ATT&CK, networking and Linux.

**Not on GitHub**
- **Online Garage Searching System** (Flutter, Firebase): finds the three nearest garages for the user's location and vehicle problem, using GPS, Google Maps and the Haversine formula.
- **Regulated DC power supply** (IOE electronics lab): bridge rectifier, capacitor filter and Zener regulator. Verified output voltage, load regulation and ripple with an oscilloscope and multimeter; troubleshot faults stage by stage.

## Thesis (in progress)

Machine-learning-based test case prioritization for continuous integration.

## Experience

**Security Researcher**, Incybrix Security, Nepal · Aug 2024 – Jan 2025 · full-time
- Security assessments and penetration tests on web applications and APIs; each finding documented with evidence.
- Python scripts to automate security operations tasks.
- Worked with development teams to build security controls into the software development lifecycle.

**Cyber Security Researcher (Intern)**, Eminence Ways, Nepal · Dec 2023 – Mar 2024
- Vulnerability assessment and penetration testing (VAPT) for enterprise clients across web apps, mobile apps and network infrastructure.
- Technical reports with risk ratings and corrective-action recommendations.

## Education

- **MSc, AI & Data Engineering**, University of Vaasa, Finland · 2025 – 2027 (expected)
  Coursework includes applied machine learning, computer vision, data governance, advanced data architecture and system integration. Project management case study with Wapice Ltd (Agile/Scrum, ISO-aligned quality management).
- **B.E., Computer Engineering**, Tribhuvan University (IOE), Nepal · 2019 – 2024
  Analog and digital circuit, digital logic and microprocessor labs.

## Certifications

- **Certified AppSec Practitioner (CAP)**, The SecOps Group, 2024
- Coursework: Security Operations Center in Practice (IBM, 2025) · Introduction to Cybersecurity Tools & Cyber Attacks (IBM) · Linux Fundamentals for Security Practitioners (Cybrary) · Python for Everybody (Coursera, 2022)

## Tools

- **Security:** Burp Suite, Nmap, Wireshark, OWASP Top 10, MITRE ATT&CK, VirusTotal, ANY.RUN
- **Code & testing:** Python, pandas, scikit-learn, Jupyter, pytest, ruff, GitHub Actions
- **Platforms:** Linux, Git, Flutter/Dart, Firebase
- **Lab equipment:** oscilloscope, digital multimeter, function generator, bench DC power supply
