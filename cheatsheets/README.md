# 📌 **Cybersecurity Cheatsheets**

This collection of **cheatsheets** provides quick references and essential information for common cybersecurity concepts, commands, and best practices. Ideal for **exam preparation, SOC analysts, penetration testers, and security engineers**.

---

## 📖 **1. Table of Contents**

- [🛡️ General Security Concepts](#-general-security-concepts)
- [🔐 Authentication & Access Control](#-authentication--access-control)
- [🌐 Network Security](#-network-security)
- [📜 Security Operations & Incident Response](#-security-operations--incident-response)
- [🕵️‍♂️ Threat Intelligence & Ethical Hacking](#-threat-intelligence--ethical-hacking)
- [📝 Compliance & Security Frameworks](#-compliance--security-frameworks)

---

## 🛡️ **2. General Security Concepts**

### 🔹 **CIA Triad** (Confidentiality, Integrity, Availability)
| Concept | Description | Example |
|---------|------------|---------|
| **Confidentiality** | Ensures data is only accessed by authorized users. | **Encryption (AES, TLS)**, MFA |
| **Integrity** | Protects data from unauthorized modification. | **Hashing (SHA-256), Digital Signatures** |
| **Availability** | Ensures services remain accessible when needed. | **Load balancing, DDoS mitigation** |

### 🔹 **Principle of Least Privilege (PoLP)**
✅ Assign users only the permissions they need.  
✅ Implement **Role-Based Access Control (RBAC)**.  
✅ Regularly audit **user permissions** to prevent privilege creep.

---

## 🔐 **3. Authentication & Access Control**

### 🔹 **Multi-Factor Authentication (MFA) Methods**
| Type | Description | Example |
|------|------------|---------|
| **Something You Know** | A password or PIN. | Account passwords |
| **Something You Have** | A physical device. | Security token, Smart card |
| **Something You Are** | Biometric authentication. | Fingerprint, Face ID |

### 🔹 **Common Authentication Protocols**
| Protocol | Description |
|----------|------------|
| **LDAP** | Directory-based authentication for user access. |
| **Kerberos** | Secure authentication using ticket-based access. |
| **SAML** | Enables Single Sign-On (SSO) for web applications. |
| **OAuth 2.0** | Open standard for API authentication. |
| **OpenID Connect** | Extends OAuth 2.0 for identity verification. |

---

## 🌐 **4. Network Security**

### 🔹 **Common Firewall Rules**
| Rule | Description |
|------|------------|
| **Allowlist (Whitelist)** | Permits only specified traffic. |
| **Blocklist (Blacklist)** | Denies specific traffic sources. |
| **Stateful Inspection** | Tracks the state of active connections. |
| **Application Layer Filtering** | Blocks traffic based on application behavior. |

### 🔹 **Common Network Security Commands**
| Command | Description |
|---------|------------|
| `netstat -an` | Displays network connections. |
| `tcpdump -i eth0` | Captures network packets. |
| `iptables -L` | Lists firewall rules in Linux. |
| `nmap -sS target.com` | Performs a stealth SYN scan. |
| `traceroute domain.com` | Traces the route packets take to a host. |

---

## 📜 **5. Security Operations & Incident Response**

### 🔹 **Incident Response (NIST SP 800-61)**
| Phase | Description |
|-------|------------|
| **Preparation** | Establish policies and playbooks. |
| **Detection & Analysis** | Identify suspicious activity. |
| **Containment** | Limit incident impact and isolate threats. |
| **Eradication** | Remove malicious artifacts and fix vulnerabilities. |
| **Recovery** | Restore services and test security postures. |
| **Lessons Learned** | Conduct post-incident reviews and update policies. |

### 🔹 **SOC (Security Operations Center) Key Logs to Monitor**
✅ **Failed Login Attempts** – Detect brute-force attacks.  
✅ **Unusual Traffic Patterns** – Identify potential exfiltration.  
✅ **Privilege Escalation Events** – Alert on unauthorized access.

---

## 🕵️‍♂️ **6. Threat Intelligence & Ethical Hacking**

### 🔹 **Cyber Kill Chain (Lockheed Martin)**
| Phase | Description |
|-------|------------|
| **Reconnaissance** | Attacker gathers intel on targets. |
| **Weaponization** | Malware or exploit development. |
| **Delivery** | Sends payload via phishing or exploitation. |
| **Exploitation** | Executes malicious payload. |
| **Installation** | Installs backdoor or persistence. |
| **Command & Control (C2)** | Gains remote control over compromised systems. |
| **Actions on Objectives** | Executes final goal (e.g., data exfiltration, ransomware). |

### 🔹 **Common Penetration Testing Tools**
| Tool | Purpose |
|------|---------|
| **Metasploit** | Exploitation framework. |
| **Burp Suite** | Web security testing. |
| **Wireshark** | Packet analysis. |
| **Nmap** | Network reconnaissance. |
| **John the Ripper** | Password cracking. |
| **Hydra** | Brute-force password attacks. |

---

## 📝 **7. Compliance & Security Frameworks**

### 🔹 **Major Security Frameworks**
| Framework | Description |
|-----------|------------|
| **NIST 800-53** | U.S. government security controls. |
| **ISO 27001** | International information security standard. |
| **CIS Controls** | Cybersecurity best practices. |
| **PCI DSS** | Payment Card Industry security standards. |
| **SOC 2** | Security compliance for SaaS providers. |
| **HIPAA** | Healthcare data security standards. |

### 🔹 **Key Security Acronyms**
✅ **SIEM** – Security Information & Event Management  
✅ **IDS/IPS** – Intrusion Detection/Prevention System  
✅ **EDR** – Endpoint Detection & Response  
✅ **MFA** – Multi-Factor Authentication  
✅ **IAM** – Identity & Access Management  
✅ **SOC** – Security Operations Center  

---

## 🔗 **8. Additional Resources**
- 📄 **[NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)**
- 🔐 **[OWASP Top 10](https://owasp.org/www-project-top-ten/)**
- 🎥 **[SANS Cybersecurity Training](https://www.sans.org/)**
- 🛡️ **[MITRE ATT&CK Framework](https://attack.mitre.org/)**

---

## 🎯 **Conclusion**

These **cheatsheets** provide **quick and effective security references** to aid cybersecurity professionals in their day-to-day operations. Continuous learning and hands-on practice are essential for mastering cybersecurity concepts!
