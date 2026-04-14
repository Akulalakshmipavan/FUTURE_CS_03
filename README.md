# 🔐 API Security Risk Analysis (SaaS-Level Project)

> 🚀 Real-world API security assessment using Kali Linux & Postman
> 💼 Simulates work done by AppSec Engineers & Security Consultants

---

## 📌 Project Overview

Modern applications rely heavily on APIs for communication between services.
This project performs a **read-only API Security Risk Analysis** on a public API to identify potential vulnerabilities and suggest remediation strategies.

🔍 The analysis focuses on:

* Authentication
* Authorization
* Data Exposure
* API Abuse Risks

---

## 🌐 API Tested

```
https://jsonplaceholder.typicode.com
```

✔️ Public test API (safe for learning)
✔️ No exploitation performed (ethical testing only)

---

## 🛠️ Tools & Environment

* 🐉 Kali Linux (VMware)
* 📬 Postman (API Testing)
* 🌐 Browser DevTools
* 🧠 Manual Security Analysis

---

## ⚙️ Methodology

1. Selected a public API
2. Sent requests using Postman
3. Observed responses and headers
4. Checked authentication requirements
5. Tested multiple endpoints
6. Identified security risks
7. Classified severity
8. Suggested remediation

---

## 🚨 Key Security Findings

### 🔴 1. No Authentication

* API allows access without login
* Anyone can retrieve user data

💥 **Impact:** Unauthorized access & data leakage

---

### 🟠 2. Excessive Data Exposure

* API returns unnecessary sensitive data

💥 **Impact:** Privacy risks & misuse of information

---

### 🔴 3. Broken Authorization

* Users can access other users’ data

💥 **Impact:** Serious data breach possibility

---

### 🟡 4. No Rate Limiting

* Unlimited API requests allowed

💥 **Impact:** API abuse & potential DoS attacks

---

## 📊 Risk Summary

| Risk                    | Severity  | Impact              |
| ----------------------- | --------- | ------------------- |
| No Authentication       | 🔴 High   | Unauthorized Access |
| Broken Authorization    | 🔴 High   | Data Breach         |
| Excessive Data Exposure | 🟠 Medium | Privacy Leakage     |
| No Rate Limiting        | 🟡 Medium | API Abuse / DoS     |

---

## 🧠 Attack Flow (How Risk Happens)

```text
1. Attacker sends API request
2. No authentication required
3. API returns sensitive data
4. Attacker collects information
5. System security is compromised
```

---

## 🛡️ Remediation Strategies

* ✅ Implement JWT / OAuth authentication
* ✅ Apply Role-Based Access Control (RBAC)
* ✅ Limit API response data
* ✅ Add rate limiting (throttling)
* ✅ Monitor API traffic

---

## 📸 Evidence

📂 Screenshots included in `/screenshots/`
🖼️ Combined evidence image added

---

## 📂 Project Structure

```
API-Security-Risk-Analysis/
│
├── README.md
├── report/
│   └── report.pdf
├── screenshots/
│   ├── request.png
│   ├── response.png
│   ├── headers.png
│   └── combined.png
```

---

## ⚠️ Disclaimer

This project is conducted in a **read-only and ethical manner**.
No exploitation, attack, or harm was performed.

---

## 💼 Why This Project Matters

✔️ Demonstrates **real-world API security skills**
✔️ Aligns with **OWASP API Top 10 risks**
✔️ Useful for:

* AppSec Engineer roles
* Security Analyst roles
* Bug Bounty beginners

---

## 🚀 Author

**Lakshmi Pavan Akula**
Cyber Security Student | API Security Enthusiast
