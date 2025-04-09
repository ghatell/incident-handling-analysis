# 🚨 Cybersecurity Incident Handling & Analysis Portfolio

This project showcases real-world incident handling and analysis examples using the **NIST Cybersecurity Framework**. It includes a simulated **incident handler journal entry** and multiple **incident report analyses** for different threat scenarios (DDoS, phishing, ransomware).

---

## 📝 Journal Entry Example

| **Date**       | **Entry** | **Description**                      |
|----------------|-----------|--------------------------------------|
| July 23, 2024  | #1        | Documented a ransomware incident     |

### 📌 Incident Details (The 5 W’s)
- **Who**: Organized group of unethical hackers  
- **What**: Ransomware attack  
- **Where**: Healthcare company  
- **When**: Tuesday, 9:00 a.m.  
- **Why**: Access gained via phishing; ransom demanded for decryption key

### 💭 Additional Notes
- How can the company prevent future incidents like this?
- Should the company pay the ransom?

---

## 📊 Incident Report #1 – DDoS Attack

> **Summary**: The company experienced a Distributed Denial of Service (DDoS) attack via an ICMP flood, causing network disruption.

### 🔐 NIST CSF Breakdown

| **Function** | **Actions Taken** |
|--------------|-------------------|
| **Identify** | Detected ICMP flood disrupting entire internal network |
| **Protect**  | Implemented firewall rules and IDS/IPS for filtering traffic |
| **Detect**   | Set up IP verification and network monitoring |
| **Respond**  | Isolated affected systems, restored critical services, analyzed logs |
| **Recover**  | Restored full network functionality in phases, prioritized critical services |

---

## 📊 Incident Report #2 – Phishing & Data Breach

> **Summary**: An intern's account was compromised via phishing. Malicious access led to unauthorized database access and data manipulation.

### 🔐 NIST CSF Breakdown

| **Function** | **Actions Taken** |
|--------------|-------------------|
| **Identify** | Intern’s credentials used to access and alter customer records |
| **Protect**  | MFA, limited login attempts, security training, IPS implementation |
| **Detect**   | Introduced firewall logging and IDS to catch future breaches |
| **Respond**  | Account disabled, users trained, breach reported to customers & law enforcement |
| **Recover**  | Restored data from backup and re-entered lost entries |

---

## 💡 Key Takeaways

- **Ransomware, DDoS, and phishing** are high-impact incidents that require rapid response and layered prevention.
- **Human error** and **weak authentication** remain top vulnerabilities.
- **Logging, backups, and employee training** are foundational to recovery and resilience.

# [📑 GRC Mapping – Incident Response & Compliance](https://github.com/ghatell/grc-mapping)

---

> **Note**: This project is part of a cybersecurity learning portfolio and uses fictional scenarios for educational purposes.
