# Threat Intelligence Portfolio

## Jessica Sansaricq

Recent Cybersecurity graduate with a strong interest in threat intelligence, malware analysis, and cyber threat investigations. This portfolio showcases hands-on projects involving phishing investigations, malware analysis, IOC analysis, and MITRE ATT&CK threat actor research.

---

## Project 1: Threat Intelligence Investigation Portfolio

This project includes a phishing investigation, malware analysis, and threat actor research using real-world cybersecurity tools and frameworks.

### Phishing Investigation

* Investigated the phishing domain **auth-login.pages.dev** using URLScan, VirusTotal, WHOIS, Shodan, and AlienVault OTX.
* Identified suspicious infrastructure, related domains, and mapped findings to the MITRE ATT&CK framework.
* File: `Phishing_Investigation_Report.pdf`

### Malware Analysis

* Analyzed the malware sample **bomb.bin** using ANY.RUN, VirusTotal, and Hybrid Analysis.
* Documented behavioral indicators, network IOCs, process activity, and MITRE ATT&CK techniques.
* File: `Malware_Analysis_Report.pdf`

### Threat Actor Analysis – Lazarus Group

* Researched Lazarus Group using the MITRE ATT&CK framework and ATT&CK Navigator.
* Identified key tactics and techniques and compared them with behaviors observed during malware analysis.
* File: `Lazarus_Group_Threat_Analysis.pdf`

---

## Project 2: Lazarus Group IOC Investigation

This project investigates three indicators of compromise linked to suspected Lazarus Group activity: a malicious file hash, a phishing domain, and an infrastructure IP address. The analysis uses VirusTotal, AlienVault OTX, Censys, and MITRE ATT&CK to understand how the indicators connect to the broader campaign.

### IOCs Analyzed

* SHA256 Hash: `dfee6ea9cafc674b93a8460b9e6beea7f0eb0c28e28d1190309347fd1514dbb6`
* Domain: `update-teams.live`
* IP Address: `144.172.114.220`

### Tools Used

* VirusTotal
* AlienVault OTX
* Censys
* MITRE ATT&CK
* Sigma
* YARA

### Key Findings

* The file hash was associated with malicious macOS activity and linked to the NukeSped malware family.
* The domain `update-teams.live` showed phishing characteristics and impersonated Microsoft Teams-related infrastructure.
* The IP address `144.172.114.220` was associated with suspicious domains and attacker infrastructure.
* Threat intelligence sources connected the indicators to Lazarus Group activity involving macOS users and ClickFix-style social engineering.
* MITRE ATT&CK mapping helped show how the attack moves from phishing, to user execution, to command-and-control activity.

### Detection and Defense

* Created basic detection logic using Sigma and YARA.
* Documented defensive recommendations for blocking malicious infrastructure.
* Mapped observed activity to MITRE ATT&CK techniques.

### Video Walkthrough

* YouTube: https://youtu.be/AgnfcYWKNzc

---

## Skills Demonstrated

* Threat Intelligence
* IOC Analysis
* Malware Analysis
* Phishing Investigations
* MITRE ATT&CK Mapping
* Threat Actor Research
* Detection Engineering
* VirusTotal
* ANY.RUN
* Hybrid Analysis
* Shodan
* AlienVault OTX
* URLScan
* Censys
* Sigma
* YARA
* Cyber Threat Research

---

## Contact

* LinkedIn: [www.linkedin.com/in/jessicasansaricq](http://www.linkedin.com/in/jessicasansaricq)
* GitHub: https://github.com/CyberGalJess
* YouTube: Project 1 | https://youtu.be/AgnfcYWKNzc
* Youtube: Project 2 | https://youtu.be/WYDtBCQct0k


## Contact
Video Walkthrough: https://youtu.be/AgnfcYWKNzc

LinkedIn: www.linkedin.com/in/jessicasansaricq

GitHub: CybergalJess
## Copyright / Usage Notice
© 2026 Jessica Sansaricq. This project is provided for educational and portfolio purposes. Please do not copy, redistribute, or present this work as your own.
