<div align="center">

# Hamdi Maissa

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2500&pause=800&color=1A2B4A&center=true&vCenter=true&width=650&lines=DevSecOps;SOC+%2F+Blue+Team;Network+Security)](#)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-1a2b4a?style=flat-square&logo=gmail&logoColor=white)](#)

</div>

---

## About

Final-year Network Security & Information Systems student at **TEK-UP University**, Tunisia. Rather than specializing too early, I've built hands-on, production-grade experience across the three pillars of a modern security team:

- **DevSecOps** — designed and hardened a CI/CD pipeline (SAST, secret scanning, SCA, container scanning) for a production e-commerce platform
- **SOC / Blue Team** — deployed a full open-source SOC stack and validated it end-to-end with real attack simulations (Nmap reconnaissance, SSH brute-force via Hydra)
- **Network Security** — designed and secured a bank's infrastructure (segmentation, hardening, high availability) during a hands-on internship at BIAT

**In active training:** RHCSA · AWS SAA-C03 · ISO 27001 Foundation
**Languages:** Arabic (native) · French (B2) · English (B2)

---

## Tech Stack

**DevSecOps & CI/CD**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-3EC94F?style=flat-square&logo=semgrep&logoColor=white)
![Gitleaks](https://img.shields.io/badge/Gitleaks-000000?style=flat-square&logo=git&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red_Hat-EE0000?style=flat-square&logo=redhat&logoColor=white)

**Security & SOC**
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-D2232A?style=flat-square)
![Wazuh](https://img.shields.io/badge/Wazuh-3AB7E1?style=flat-square)
![TheHive](https://img.shields.io/badge/TheHive-FF3E3E?style=flat-square)
![Shuffle](https://img.shields.io/badge/Shuffle-6C5CE7?style=flat-square)

**Offensive / Web Security**
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)

**Networks & Cloud**
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![GNS3](https://img.shields.io/badge/GNS3-2E7D32?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white)

**Development & Data**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

---

## Featured Projects

### 🛡️ [Open-Source SOC](https://github.com/maissahamdi047-sys/SOC)
Deployed a full open-source Security Operations Center in a segmented **WAN/LAN/DMZ** environment, covering the complete **Monitor → Detect → Analyse → Respond** cycle. Validated end-to-end with real attack simulations (Nmap reconnaissance, SSH brute-force via Hydra) traced from detection through alerting and incident case management.

`pfSense` `Suricata` `Wazuh` `TheHive` `Shuffle` `Kali Linux` `VMware`

### 🌐 [Enterprise Network Architecture](https://github.com/maissahamdi047-sys/Network-Architecture-and-Security)
End-to-end enterprise network design in GNS3: an IP/MPLS backbone with **VRF** and **MP-BGP** for multi-site interconnection, a fully redundant LAN (**HSRP**, **EtherChannel**, **OSPF**), and centralized supervision via **AAA/RADIUS** and **SNMPv3**.

`GNS3` `Cisco IOS` `MPLS` `OSPF` `Zabbix` `VMware`

### 🛒 [King Shopping — Secured E-Commerce Platform](https://github.com/maissahamdi047-sys/king-shopping) `Private`
Full-stack e-commerce platform with security integrated into every stage of the delivery pipeline. Designed and hardened a CI/CD pipeline on GitHub Actions (self-hosted runner) integrating **SAST** (Semgrep), **secret scanning** (Gitleaks), **SCA** (OWASP Dependency-Check), and **container scanning** (Trivy) on every push. Full backend test suite; hardened Docker multi-stage builds to shrink the production image's attack surface.

`Spring Boot` `Next.js` `FastAPI` `MySQL` `Docker` `GitHub Actions` `Trivy` `Semgrep` `Gitleaks`

### 🦠 [AsyncRAT — Malware Analysis](https://github.com/maissahamdi047-sys/AsyncRAT)
Static, dynamic, and automated analysis of a live AsyncRAT sample: sandbox detonation (VirusTotal, ANY.RUN, Hybrid Analysis, MetaDefender), static analysis of the packed PE binary (Detect-It-Easy, FLOSS), and local dynamic analysis confirming process hollowing and Startup-folder persistence. Full MITRE ATT&CK mapping and detection recommendations.

`VirusTotal` `ANY.RUN` `Hybrid Analysis` `Process Hacker` `Process Monitor` `FLOSS`

### 🔍 [OWASP Top 10 (2021) Assessment — Juice Shop](https://github.com/maissahamdi047-sys/Juice_shop)
Full vulnerability assessment against the OWASP Top 10 using the intentionally vulnerable Juice Shop application: attack vector per vulnerability class, proof-of-exploitation, business impact, and remediation recommendations.

`Burp Suite` `Kali Linux` `Hashcat` `OWASP`

### 🖥️ [GOAD Lab — Active Directory Pentesting](https://github.com/maissahamdi047-sys/GOAD_Lab)
Hands-on Active Directory penetration testing lab built on GOAD (Game Of Active Directory): enumeration, lateral movement, and privilege escalation techniques (Kerberoasting, ACL abuse, pass-the-hash) practiced against a deliberately vulnerable multi-domain environment.

`Active Directory` `BloodHound` `Impacket` `Kali Linux`

### 🔐 [Recon — Facial Recognition Security System](https://github.com/maissahamdi047-sys/Biometrics)
Biometric access control system: facial recognition (LBPH), low-light detection, **AES-256** encryption of stored images and database, **LSB digital watermarking** of access logs for tamper-evidence, GDPR-compliant design.

`Python` `OpenCV` `LBPH` `Cryptography` `AES-256` `Tkinter`

### 🦷 [Dental Clinic Management System](https://github.com/maissahamdi047-sys/Dental-Clinic)
Full-stack medical practice platform: patients, scheduling, invoicing, PDF reports, Stripe payments.

`Symfony` `PHP` `MySQL` `Stripe` `DomPDF`

### 🌍 [Tunisco — Tourism Platform](https://github.com/maissahamdi047-sys/TUNISCO) `Private`
Tunisia tourism platform with an interactive map and booking flow.

`HTML5` `CSS3` `JavaScript`

### 🤖 [Mars AI Assistant](https://github.com/maissahamdi047-sys/chatbot)
Multi-model chatbot (Groq & Gemini) with voice input and file upload.

`Python` `Streamlit` `Groq` `Gemini`

### 🎮 [Hangman Game](https://github.com/maissahamdi047-sys/Hangman_Game)
Graphical Hangman implementation with a full JavaFX interface.

`Java` `JavaFX` `Maven`

### 🔐 [Educational Ransomware Simulation](https://github.com/maissahamdi047-sys/Ransomware) `Private`
⚠️ *Strictly academic, isolated environment only.* Simulated attack chain (encryption, C2 server, decryption) built to study attacker mechanics for detection and response purposes.

`Python` `Flask` `Cryptography`

---

## Experience

**Network Architecture Design Intern, Banking Infrastructure**
*BIAT Innovation & Technology · Jul. 2025 – Present · La Goulette, Tunisia · Hybrid*

Designed and secured a complete bank network infrastructure using the Collapsed Core approach:
- **Segmentation** — isolated critical services with VLANs
- **Hardening** — implemented ACLs and traffic filtering policies
- **Secure routing** — configured OSPF and BGP for inter-site connectivity
- **High availability** — deployed HSRP, EtherChannel, and Spanning Tree
- **Centralized services** — rolled out DHCP across the infrastructure

**DevSecOps Intern — King Shopping**
*TEK-UP University · 2026*

Internship built around delivering a secured e-commerce platform end-to-end, with security integrated across the delivery lifecycle. (Full technical breakdown under Featured Projects above.)

---

## Certifications

| Certification | Status |
|---|---|
| RHCSA — Red Hat Certified System Administrator | 📚 In training |
| AWS Certified Solutions Architect – Associate (SAA-C03) | 📚 In training |
| ISO 27001 Foundation | 📚 In training |

---

## Get In Touch

Actively looking for a **DevSecOps, SOC, or Network Security internship (PFE 2026–2027)**. If any of the work above is a fit for your team, let's talk.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-1a2b4a?style=flat-square&logo=gmail&logoColor=white)](#)
