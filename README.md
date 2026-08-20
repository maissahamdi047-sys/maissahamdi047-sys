<div align="center">

# Hi I'm Maissa Hamdi

### Cybersecurity Engineering Student — DevSecOps · SOC · Network Security

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=18&duration=2800&pause=900&color=C2185B&center=true&vCenter=true&width=600&lines=Securing+CI%2FCD+pipelines+from+the+first+commit;Deploying+and+tuning+open-source+SOC+stacks;Designing+segmented%2C+hardened+network+architecture)](https://github.com/maissahamdi047-sys)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-D46A9F?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maissa-hamdi-04a75a390)
[![Email](https://img.shields.io/badge/Email-C2185B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maissahamdi047@gmail.com)
[![views](https://komarev.com/ghpvc/?username=maissahamdi047-sys&style=for-the-badge&color=D46A9F&label=PROFILE+VIEWS)](https://github.com/maissahamdi047-sys)

</div>

---

## About

4th-year Engineering student in Network Security and Information Systems (ING-4-SSIR) at Tek-Up University, Tunisia. I build systems with security integrated by design, and I've deliberately developed hands-on experience across the three roles that make up a modern security team — **DevSecOps**, **SOC/Blue Team**, and **Network Security** — rather than narrowing too early.

**What that looks like in practice:**
- Designed and hardened a full DevSecOps CI/CD pipeline for a production e-commerce platform (SAST, secret scanning, SCA, container scanning)
- Deployed and validated a complete open-source SOC stack, with real attack simulations traced end-to-end through detection and response
- Secured a bank's network infrastructure during a hands-on internship at BIAT

📚 Currently training for **RHCSA**, **AWS SAA-C03**, and **ISO 27001 Foundation**
🗣️ Arabic (native) · French (B2) · English (B2)

---

## Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**DevSecOps & CI/CD**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat&logo=aquasecurity&logoColor=white) ![Semgrep](https://img.shields.io/badge/Semgrep-000000?style=flat&logo=semgrep&logoColor=white) ![Gitleaks](https://img.shields.io/badge/Gitleaks-FFB300?style=flat)

**Security & SOC**
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat&logo=pfsense&logoColor=white) ![Suricata](https://img.shields.io/badge/Suricata-EF7E1A?style=flat&logo=suricata&logoColor=white) ![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat&logo=wazuh&logoColor=white) ![TheHive](https://img.shields.io/badge/TheHive-FFBE00?style=flat&logo=hive&logoColor=black) ![Shuffle](https://img.shields.io/badge/Shuffle-7B68EE?style=flat)

**Web Security**
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat&logo=burpsuite&logoColor=white) ![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat&logo=kalilinux&logoColor=white) ![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat&logo=owasp&logoColor=white)

</td>
<td valign="top" width="50%">

**Networks & Cloud**
![Cisco](https://img.shields.io/badge/Cisco_IOS-1BA0D7?style=flat&logo=cisco&logoColor=white) ![GNS3](https://img.shields.io/badge/GNS3-FF6C37?style=flat) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white) ![Red Hat](https://img.shields.io/badge/Red_Hat-EE0000?style=flat&logo=redhat&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat&logo=zabbix&logoColor=white)

**Development**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Databases**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

</td>
</tr>
</table>

---

## Featured Projects

### 🛒 King Shopping — Secured E-commerce Platform · DevSecOps
`In Progress`

Full-stack e-commerce platform with security integrated into every stage of the delivery pipeline. Designed and hardened a CI/CD pipeline on GitHub Actions (self-hosted runner) integrating static analysis (Semgrep), secret scanning (Gitleaks), dependency scanning (OWASP Dependency-Check), and container vulnerability scanning (Trivy) on every push. Full backend test suite (JUnit 5, Mockito) across ~20 services and 19 controllers; hardened Docker multi-stage builds to reduce the production image's attack surface.

**Stack:** Spring Boot · Next.js · FastAPI · MySQL · Docker · GitHub Actions · Trivy · Semgrep · Gitleaks
📂 [Repository](https://github.com/maissahamdi047-sys/king-shopping)

### 🛡️ Open-Source SOC Lab — pfSense · Wazuh · Suricata · TheHive · Shuffle
`Final-Year Project`

Full deployment of an open-source Security Operations Center in a segmented WAN/LAN/DMZ environment, covering the complete **Monitor → Detect → Analyze → Respond** cycle. Validated with real attack simulations — Nmap reconnaissance and SSH brute-force via Hydra — traced end-to-end from detection through alerting and case management.

**Stack:** pfSense · Suricata · Wazuh · TheHive · Shuffle · Kali Linux · VMware
📹 Demo available on request

### 🌐 Enterprise Network Architecture — VPN-MPLS · Redundant LAN · Monitoring

End-to-end enterprise network design in GNS3: an IP/MPLS backbone with VRF and MP-BGP for multi-site interconnection, a fully redundant LAN (HSRP, EtherChannel, OSPF), and centralized supervision via AAA/RADIUS and SNMPv3.

**Stack:** GNS3 · Cisco IOS · MPLS · OSPF · Zabbix · VMware
📹 Demo available on request

### 🔍 OWASP Top 10 (2021) Assessment — Juice Shop

Full vulnerability assessment against the OWASP Top 10 using the intentionally vulnerable Juice Shop application: attack vector per vulnerability class, proof-of-exploitation, business impact, and remediation recommendations.

**Stack:** Burp Suite · Kali Linux · Hashcat · OWASP
📹 [Watch demo](https://github.com/maissahamdi047-sys/juice_shop/releases/download/v1.5/Enregistrement.de.l.ecran.2026-03-10.060319.mp4)

### 🔐 Recon — Facial Recognition Security System

Biometric security system: facial recognition (LBPH), low-light detection, AES-256 encryption of stored images and database, LSB digital watermarking of access logs for tamper-evidence, GDPR-compliant design.

**Stack:** Python · OpenCV · LBPH · Cryptography · AES-256 · Tkinter
📹 Demo available on request

<details>
<summary><b>Other projects</b> — web development, applied AI (click to expand)</summary>
<br>

**🦷 Dental Clinic Management System** — Full-stack medical practice platform: patients, scheduling, invoicing, PDF reports, Stripe payments.
Stack: Symfony · PHP · MySQL · Stripe · DomPDF · [Demo](https://github.com/maissahamdi047-sys/cabinet-dentaire/releases/download/v1.2/Enregistrement.2026-06-18.212640.mp4)

**🌍 Tunisco** — Tunisia tourism platform with interactive map and booking flow.
Stack: HTML5 · CSS3 · JavaScript · [Demo](https://github.com/maissahamdi047-sys/TUNISCO/releases/download/v1.3/1777157875891.jpg)

**🤖 Mars AI Assistant** — Multi-model chatbot (Groq & Gemini) with voice input and file upload.
Stack: Python · Streamlit · Groq · Gemini · [Demo](https://github.com/maissahamdi047-sys/chatbot/releases/download/v1.4/1750979190287.jpg)

**🎮 Hangman Game** — Graphical Hangman implementation with a full JavaFX interface.
Stack: Java · JavaFX · Maven · [Demo](https://github.com/maissahamdi047-sys/Hangman-Game/releases/download/v1.1/Enregistrement.2026-06-20.182200.mp4)

**🔐 Educational Ransomware Simulation** — ⚠️ Strictly academic, isolated environment only. Simulated attack chain (encryption, C2 server, decryption) built to study attacker mechanics for detection and response purposes.
Stack: Python · Flask · Cryptography · [Demo](https://github.com/maissahamdi047-sys/Ransomware/releases/download/v1.0/Scenario.mp4)

</details>

---

## Experience

**BIAT Innovation & Technology** — Network Architecture Design Intern, Banking Infrastructure
*Jul. 2025 – Present · La Goulette, Tunisia · Hybrid*

Designed and secured a complete bank network infrastructure following the Collapsed Core approach:
- **Segmentation** — isolated critical services using VLANs
- **Hardening** — implemented ACLs and traffic filtering policies
- **Secure routing** — configured OSPF and BGP for inter-site connectivity
- **High availability** — deployed HSRP, EtherChannel, and Spanning Tree
- **Centralized services** — rolled out DHCP across the infrastructure

**King Shopping** — DevSecOps Project, Tek-Up Academic Project
*2026*

Full-stack e-commerce platform built for a client, with security integrated across the delivery lifecycle:
- **CI/CD pipeline** — designed and hardened a GitHub Actions pipeline on a self-hosted runner
- **Security scanning** — integrated SAST, secret scanning, and SCA
- **Container security** — vulnerability scanning and hardened Docker builds
- **Test coverage** — full backend test suite across ~20 services and 19 controllers

---

## Certifications

*In active training — not yet certified*

| Certification | Status |
|---|---|
| RHCSA — Red Hat Certified System Administrator | 📚 In training |
| AWS Certified Solutions Architect – Associate (SAA-C03) | 📚 In training |
| ISO 27001 Foundation | 📚 In training |

---

## GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=maissahamdi047-sys&show_icons=true&hide_border=true&count_private=true&theme=radical" width="48%">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=maissahamdi047-sys&layout=compact&hide_border=true&langs_count=8&theme=radical" width="48%">
</p>

<p align="center">
<img src="https://streak-stats.demolab.com/?user=maissahamdi047-sys&hide_border=true&theme=radical" width="60%">
</p>

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=maissahamdi047-sys&theme=radical&no-frame=true&column=7&margin-w=8">
</p>

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:D46A9F,100:9C6BA0&height=110&section=footer&text=Open%20to%20DevSecOps%20%2F%20SOC%20%2F%20Network%20Security%20Internships&fontSize=15&fontColor=ffffff&fontAlignY=70">
</p>
