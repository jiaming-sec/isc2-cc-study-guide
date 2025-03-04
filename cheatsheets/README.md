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
