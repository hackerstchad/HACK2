# HACK

## 📌 Table des matières

1. [Introduction](#introduction)
2. [Mindmap des compétences](#mindmap-des-compétences)
3. [Fondamentaux informatiques](#fondamentaux-informatiques)
4. [Réseaux & Protocoles](#réseaux--protocoles)
5. [Systèmes d'exploitation](#systèmes-dexploitation)
6. [Programmation pour la sécurité](#programmation-pour-la-sécurité)
7. [Hacking web](#hacking-web)
8. [Tests d'intrusion réseau](#tests-dintrusion-réseau)
9. [Reverse engineering & malware analysis](#reverse-engineering--malware-analysis)
10. [OSINT & ingénierie sociale](#osint--ingénierie-sociale)
11. [Cryptographie](#cryptographie)
12. [Forensics & incident response](#forensics--incident-response)
13. [Bug bounty & programs](#bug-bounty--programs)
14. [Certifications](#certifications)
15. [Labs & plateformes de pratique](#labs--plateformes-de-pratique)
16. [Communautés africaines & francophones](#communautés-africaines--francophones)
17. [Ressources par langue](#ressources-par-langue)
18. [Feuille de route 12 mois](#feuille-de-route-12-mois)
19. [Glossaire](#glossaire)
20. [Contribuer](#contribuer)

---

## Introduction

Ce guide vise à former des professionnels de la cybersécurité responsables. Il couvre les domaines du pentest, de la défense (blue team), de l'analyse de malware, du bug bounty et de la recherche en sécurité.

### Code d'éthique

- Ne jamais tester sans autorisation.
- Respecter la vie privée et les données personnelles.
- Divulguer les vulnérabilités de manière responsable.
- Contribuer à la sécurisation des systèmes, pas à leur destruction.

---

## Mindmap des compétences

```text
Cybersécurité
├── Red Team (offensif)
│   ├── Pentest web
│   ├── Pentest réseau
│   ├── Social engineering
│   ├── Exploit development
│   └── Physical security
├── Blue Team (défensif)
│   ├── SOC / SIEM
│   ├── Incident response
│   ├── Threat hunting
│   └── Forensics
├── Purple Team
│   ├── Simulation d'APT
│   ├── Détection & atténuation
│   └── Amélioration continue
└── Governance, Risk & Compliance
    ├── Audit
    ├── Normes (ISO 27001, NIST, PCI-DSS)
    └── Gestion des risques
```

---

## Fondamentaux informatiques

### Concepts essentiels

- Modèle OSI et TCP/IP
- Systèmes binaires, hexadécimaux, ASCII/Unicode
- Architecture CPU, mémoire, stockage
- Virtualisation et conteneurs
- Bases de données relationnelles et NoSQL

### Ressources

- [CS50 — Harvard](https://cs50.harvard.edu/x/)
- [NAND2Tetris](https://www.nand2tetris.org/)
- [OpenSecurityTraining.info](http://opensecuritytraining.info/)
- [Professor Messer — CompTIA A+](https://www.professormesser.com/free-a-plus-training/220-1101/220-1101-video/220-1101-training-course/)
- [freeCodeCamp — Computer Science](https://www.freecodecamp.org/)

---

## Réseaux & Protocoles

### Protocoles à maîtriser

- TCP, UDP, IP, ICMP
- DNS, DHCP, ARP
- HTTP/HTTPS, SSL/TLS
- SSH, FTP/SFTP, SMTP, SNMP
- VPN (IPSec, WireGuard, OpenVPN)
- Wi-Fi (802.11, WPA2/WPA3)

### Outils

- Wireshark, tcpdump, tshark
- Nmap, Masscan, Zmap
- Netcat, Socat
- Burp Suite, OWASP ZAP
- Metasploit Framework
- Bettercap, Ettercap,Responder

### Ressources

- [Wireshark Certified Network Analyst](https://www.wireshark.org/)
- [Nmap Network Scanning (livre)](https://nmap.org/book/)
- [Practical Packet Analysis](https://www.nostarch.com/packetanalysis3)
- [Cybrary — Network Fundamentals](https://www.cybrary.it/)
- [Cisco Networking Academy](https://www.netacad.com/)

---

## Systèmes d'exploitation

### Linux

- Structure du système de fichiers
- Gestion des utilisateurs et permissions
- Shell scripting (bash, zsh)
- Compilation depuis les sources
- systemd, logs, cron

### Windows

- Architecture Windows
- Active Directory
- PowerShell
- Registry, services, WMI
- Sécurité Windows Defender, AppLocker

### Ressources

- [OverTheWire — Bandit](https://overthewire.org/wargames/bandit/)
- [Linux Journey](https://linuxjourney.com/)
- [Pentester Academy — Windows Forensics](https://www.pentesteracademy.com/)
- [ADSecurity — Sean Metcalf](https://adsecurity.org/)
- [The Windows Internals books](https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/)

---

## Programmation pour la sécurité

### Langages recommandés

| Langage | Usage principal |
|---------|-----------------|
| Python | Automatisation, scripts, exploits PoC |
| Bash/PowerShell | Administration système |
| C/C++ | Reverse engineering, exploits bas niveau |
| JavaScript/Node.js | Web security |
| SQL | Injection, analyse de bases |
| Assembly | Reverse engineering, shellcodes |
| Go/Rust | Outils modernes de sécurité |

### Ressources

- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- [Python for Security](https://github.com/PacktPublishing/Python-for-Offensive-PenTest)
- [Hacker101](https://www.hacker101.com/)
- [PwnCollege](https://pwn.college/)
- [OpenSecurityTraining — Assembly](http://opensecuritytraining.info/IntroX86.html)

---

## Hacking web

### Vulnérabilités OWASP Top 10

1. Broken Access Control
2. Cryptographic Failures
3. Injection (SQL, NoSQL, Command, LDAP)
4. Insecure Design
5. Security Misconfiguration
6. Vulnerable and Outdated Components
7. Identification and Authentication Failures
8. Software and Data Integrity Failures
9. Security Logging and Monitoring Failures
10. Server-Side Request Forgery (SSRF)

### Outils

- Burp Suite Professional/Community
- OWASP ZAP
- SQLMap
- Nikto, Dirb/Dirbuster, Gobuster
- XSStrike, Commix
- Postman, cURL

### Ressources

- [OWASP Top 10](https://owasp.org/Top10/)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [Web Security Academy Labs](https://portswigger.net/web-security/all-labs)
- [Bug Bounty Hunter Methodology](https://github.com/jhaddix/tbhm)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)

---

## Tests d'intrusion réseau

### Méthodologie

1. Reconnaissance (passive/active)
2. Scanning & enumeration
3. Vulnerability assessment
4. Exploitation
5. Post-exploitation
6. Reporting

### Outils

- Metasploit Framework
- Cobalt Strike (licence commerciale)
- Sliver, Empire/Starkiller
- BloodHound, SharpHound
- Mimikatz, Rubeus, Impacket
- CrackMapExec

### Ressources

- [Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/)
- [Pentestmonkey](https://pentestmonkey.net/)
- [HackTricks](https://book.hacktricks.xyz/)
- [ired.team](https://www.ired.team/)
- [Pentest Standard](http://www.pentest-standard.org/index.php/Main_Page)

---

## Reverse engineering & malware analysis

### Concepts

- Analyse statique vs dynamique
- Déassembleurs (IDA Pro, Ghidra, Binary Ninja)
- Debuggers (x64dbg, GDB, WinDbg, OllyDbg)
- Sandboxing (Cuckoo, ANY.RUN, Joe Sandbox)
- Forensic de mémoire (Volatility)

### Ressources

- [Ghidra](https://ghidra-sre.org/)
- [Reverse Engineering for Beginners](https://beginners.re/)
- [Practical Malware Analysis](https://nostarch.com/malware)
- [MalwareUnicorn — Reverse Engineering](https://malwareunicorn.org/workshops/re101.html)
- [Binary Exploitation / Pwn](https://pwnable.kr/)

---

## OSINT & ingénierie sociale

### Techniques OSINT

- Recherche Google avancée (dorks)
- WHOIS, DNS, subdomain enumeration
- Réseaux sociaux et géolocalisation
- Leaks de données (légaux et éthiques)
- Reconnaissance d'images et métadonnées

### Outils

- Maltego, theHarvester
- Sherlock, Spiderfoot
- Shodan, Censys, Fofa
- ExifTool, Metagoofil
- OSINT Framework

### Ressources

- [OSINT Framework](https://osintframework.com/)
- [Bellingcat — Online Investigation Toolkit](https://docs.google.com/document/d/1BfLPJpRtyq4WFtuaJoQaroHniX1lbT3Abo0z1T0zQgY/edit)
- [Trace Labs](https://www.tracelabs.org/)
- [IntelTechniques](https://inteltechniques.com/)

---

## Cryptographie

### Concepts

- Chiffrement symétrique vs asymétrique
- Hachage, salage, HMAC
- PKI, certificats SSL/TLS
- Protocoles modernes (AES, RSA, ECC, ChaCha20)
- Attaques classiques (MITM, replay, padding oracle)

### Ressources

- [Cryptohack](https://cryptohack.org/)
- [Cryptopals](https://cryptopals.com/)
- [Serious Cryptography](https://nostarch.com/seriouscrypto)
- [Coursera — Cryptography I (Dan Boneh)](https://www.coursera.org/learn/crypto)

---

## Forensics & incident response

### Domaines

- Analyse de disque (Autopsy, Sleuth Kit)
- Analyse mémoire (Volatility)
- Analyse de logs (Splunk, ELK, Sigma)
- Analyse réseau (Wireshark, NetworkMiner)
- Chaîne de conservation des preuves

### Ressources

- [SANS DFIR Resources](https://www.sans.org/digital-forensics-incident-response/)
- [13Cubed](https://www.13cubed.com/)
- [Volatility Foundation](https://www.volatilityfoundation.org/)
- [Velociraptor](https://docs.velociraptor.app/)

---

## Bug bounty & programs

### Plateformes

- HackerOne
- Bugcrowd
- Intigriti
- YesWeHack
- Open Bug Bounty
- Synack

### Ressources

- [HackerOne Hacktivity](https://hackerone.com/hacktivity)
- [Bugcrowd University](https://www.bugcrowd.com/hackers/bugcrowd-university/)
- [Hacker101](https://www.hacker101.com/)
- [Bug Bounty Methodology v4](https://github.com/jhaddix/tbhm)

---

## Certifications

| Certification | Niveau | Focus |
|---------------|--------|-------|
| CompTIA Security+ | Débutant | Fondamentaux |
| eJPT | Débutant/Intermédiaire | Pentest junior |
| PNPT | Intermédiaire | Pentest pratique |
| OSCP | Avancé | Pentest offensif |
| OSWE | Avancé | Web exploitation |
| OSEP | Avancé | Evasion de défenses |
| CEH | Intermédiaire | Pentest (théorique/pratique) |
| CISSP | Expert | Management sécurité |
| GCIH / GCFA | Expert | Incident response / forensics |
| CRTO | Avancé | Red team |

---

## Labs & plateformes de pratique

### Gratuits

- [OverTheWire](https://overthewire.org/wargames/)
- [picoCTF](https://picoctf.org/)
- [TryHackMe — rooms gratuites](https://tryhackme.com/)
- [HackTheBox — machines gratuites](https://www.hackthebox.com/)
- [VulnHub](https://www.vulnhub.com/)
- [PentesterLab](https://pentesterlab.com/)
- [Root-Me](https://www.root-me.org/)
- [CyberDefenders](https://cyberdefenders.org/)

### Payants

- [TryHackMe](https://tryhackme.com/)
- [HackTheBox](https://www.hackthebox.com/)
- [Pentester Academy](https://www.pentesteracademy.com/)
- [Immersive Labs](https://immersivelabs.com/)
- [TCM Security Academy](https://academy.tcm-sec.com/)

---

## Communautés africaines & francophones

- [AfriSecure](https://afrisecure.org/)
- [Cyber Africa Forum](https://cyberafricaforum.com/)
- [Honeynet Project — African chapters](https://www.honeynet.org/)
- [OWASP Francophone](https://owasp.org/www-chapter-france/)
- [ComCyber (France)](https://www.defense.gouv.fr/comcyber)
- [ANSSI (France)](https://www.ssi.gouv.fr/)
- Discord/LinkedIn : groupes CTF et cybersécurité africains

---

## Ressources par langue

### Français

- [ANSSI — Guides et recommandations](https://www.ssi.gouv.fr/guide/)
- [MISC Magazine](https://www.miscmag.com/)
- [ComCyber — MOOC](https://www.defense.gouv.fr/comcyber)
- [Zeste de Savoir — sécurité](https://zestedesavoir.com/)

### Anglais

- [SANS Internet Storm Center](https://isc.sans.edu/)
- [Krebs on Security](https://krebsonsecurity.com/)
- [Dark Reading](https://www.darkreading.com/)
- [The Hacker News](https://thehackernews.com/)
- [Schneier on Security](https://www.schneier.com/)

### Arabe

- [Arab Security Cyber Wargames](https://cyberhub.sa/)
- [CyberTalents — challenges](https://cybertalents.com/)

---

## Feuille de route 12 mois

### Mois 1–2 : Fondamentaux
- Linux, réseaux, Python, shell
- CS50 ou équivalent

### Mois 3–4 : Réseaux & sécurité offensive de base
- Nmap, Wireshark, Metasploit de base
- OverTheWire Bandit, Natas

### Mois 5–6 : Web hacking
- OWASP Top 10, PortSwigger Academy
- Burp Suite, SQLMap

### Mois 7–8 : Active Directory & réseau interne
- AD basics, BloodHound, CrackMapExec
- Labs HackTheBox/ProLabs

### Mois 9–10 : Spécialisation
- Reverse engineering, malware analysis, ou OSINT
- CTFs spécialisés

### Mois 11–12 : Certification & bug bounty
- Préparation eJPT/PNPT/OSCP
- Participation à des bug bounties éthiques

---

## Glossaire

- **APT** : Advanced Persistent Threat
- **CVE** : Common Vulnerabilities and Exposures
- **CVSS** : Common Vulnerability Scoring System
- **IDS/IPS** : Intrusion Detection/Prevention System
- **SIEM** : Security Information and Event Management
- **SOC** : Security Operations Center
- **PoC** : Proof of Concept
- **RCE** : Remote Code Execution
- **SSRF** : Server-Side Request Forgery
- **XSS** : Cross-Site Scripting

---

## Contribuer

Les contributions sont les bienvenues sous forme de pull requests. Toute ressource ajoutée doit être légale, éthique et éducative.

---

## Licence

Ce document est fourni à titre éducatif. L'auteur ne saurait être tenu responsable d'une utilisation illégale ou malveillante de son contenu.
