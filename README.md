# LoginSystemThreatModel

This project contains a STRIDE-based threat model for a simple username/password login system. The goal was to identify potential security threats, analyze how they map to STRIDE categories, and propose mitigations to improve the system’s security posture.

---

## 📘 Project Overview

The threat model evaluates a basic login workflow where a user submits credentials that are validated against stored values. The analysis focuses on identifying risks related to authentication, data handling, and system behavior.

The full threat model includes:

- System overview
- Data flow diagram (DFD)
- Asset identification
- STRIDE threat table
- Recommended mitigations

All details are documented in the attached PDF.

---

## 🧩 Key Findings (High-Level)

- Risks related to credential spoofing and brute-force attempts  
- Potential tampering with stored credentials  
- Lack of logging (repudiation risk)  
- Plaintext credential exposure  
- Denial-of-service through repeated login attempts  
- Weak validation leading to privilege escalation  

---

## 🛡 Recommended Mitigations (High-Level)

- MFA  
- HTTPS  
- Secure password storage (hashing)  
- Account lockout  
- Input validation  
- Secure logging  

---

## 📎 Included File

- [LoginSystemThreatModel.pdf](LoginSystemThreatModel.pdf) — Full threat model document
