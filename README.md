<div align="center">

# Rawley Chirume

### SOC Analyst · Cloud Security Engineering · DevSecOps

[![Security+](https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white)](#)
[![ISC2 CC](https://img.shields.io/badge/ISC²-Certified_in_Cybersecurity-00A98F?style=for-the-badge&logo=isc2&logoColor=white)](#)
[![TryHackMe SAL1](https://img.shields.io/badge/TryHackMe-SAL1_Certified-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/DartMouthWrld)

[![Email](https://img.shields.io/badge/Email-chirumerawley%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:chirumerawley@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rawleyc-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rawleyc)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_1%25-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/DartMouthWrld)
[![GitHub](https://img.shields.io/badge/GitHub-rawleyc-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rawleyc)

🎓 B.Sc. Computer Science — Lubelska Akademia WSEI · 📍 Lublin, Poland

</div>

---

## 🧭 Professional Summary

Security-focused IT professional with hands-on SOC training and cloud security engineering experience. **Ranked Top 1% on TryHackMe** with practical exposure to log analysis, incident triage, and threat detection workflows. Experienced in monitoring AWS environments, analyzing authentication activity, and implementing **automated containment mechanisms** to mitigate security incidents. Passionate about helping organizations detect, investigate, and respond to security threats in real time.

---

## 🔀 Career Trajectory — Where Cybersecurity Meets Cloud

```mermaid
graph LR
    subgraph CYBER["🛡️ CYBERSECURITY"]
        A1[Incident Triage &\nThreat Detection]
        A2[Log Analysis &\nSIEM Monitoring]
        A3[Network &\nTraffic Analysis]
    end

    subgraph CLOUD["☁️ CLOUD ENGINEERING"]
        B1[AWS IAM &\nIdentity Management]
        B2[Serverless &\nEvent-Driven Architecture]
        B3[Infrastructure &\nAutomation]
    end

    subgraph DEVSECOPS["🔒 DEVSECOPS — THE CONVERGENCE"]
        C1[Cloud Security\nEngineering]
        C2[Automated Incident\nResponse]
        C3[Security-as-Code &\nCI/CD Hardening]
    end

    A1 --> C1
    A2 --> C2
    A3 --> C3
    B1 --> C1
    B2 --> C2
    B3 --> C3

    style CYBER fill:#1a1a2e,stroke:#e94560,stroke-width:2px,color:#eee
    style CLOUD fill:#1a1a2e,stroke:#0f3460,stroke-width:2px,color:#eee
    style DEVSECOPS fill:#16213e,stroke:#00b4d8,stroke-width:3px,color:#eee
    style C1 fill:#0f3460,stroke:#00b4d8,color:#eee
    style C2 fill:#0f3460,stroke:#00b4d8,color:#eee
    style C3 fill:#0f3460,stroke:#00b4d8,color:#eee
```

> *One foot in **Cybersecurity**, the other in **Cloud** — meeting in the middle at **DevSecOps**.*

---

## 🎯 What I Do

| Domain | Focus |
|--------|-------|
| 🔍 **Detect & Respond** | Incident triage, alert escalation, root cause analysis, and real-time threat detection using SIEM platforms |
| 🛡️ **Secure Identities** | AWS IAM policy enforcement, Active Directory administration, least-privilege access, and Kerberos/LDAP analysis |
| ☁️ **Cloud Security Engineering** | Event-driven security pipelines with CloudTrail, Lambda, and SNS for automated containment and alerting |
| 🔗 **Network Analysis** | TCP/IP traffic inspection, DNS investigation, and port-level analysis using Wireshark |
| ⚙️ **Automate & Harden** | Python (Boto3) scripting for security automation, CI/CD pipeline hardening, and infrastructure-as-code |

---

## 🚀 Featured Projects

### **1. [Cloud Security Automation Lab](https://github.com/rawleyc/cloud-security-automation)** &nbsp; `Mar 2026`

![AWS CloudTrail](https://img.shields.io/badge/CloudTrail-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=aws-lambda&logoColor=white)
![AWS IAM](https://img.shields.io/badge/IAM-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![SNS](https://img.shields.io/badge/SNS-FF4F8B?style=flat&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**A mini SOC built in AWS — automated cloud threat detection and incident response pipeline.**

- 🔍 **Detection:** Built an automated threat detection pipeline ingesting **CloudTrail** logs via serverless event triggers.
- 🚨 **Containment:** Implemented automated incident containment by attaching **restrictive IAM policies** when suspicious activity is detected.
- ⚡ **Response Time:** Reduced incident response time from **hours → seconds** through automated alerting and response workflows.
- 📢 **Alerting:** Configured **SNS** to notify security teams immediately of high-risk access events.

---

### **2. [Enterprise Identity Infrastructure (AWS/AD)](https://github.com/rawleyc/enterprise-identity-lab)** &nbsp; `Jan 2026`

![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat&logo=windows&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Networking](https://img.shields.io/badge/Networking-VPC_&_DNS-success?style=flat&logo=cisco&logoColor=white)

**Fault-tolerant AWS infrastructure integrated with Active Directory identity management — replacing legacy on-premise systems.**

- ☁️ **High Availability:** Deployed **AWS Managed Microsoft AD** across multiple Availability Zones.
- 🛡️ **Access Control:** Configured Group Policies and enforced **least-privilege access** for all user accounts.
- 🔗 **Networking:** Engineered secure VPC DNS resolution and DHCP Option Sets for seamless domain discovery.
- 📄 **Audit-Ready:** Documented infrastructure architecture and access management procedures for security auditing.

---

### **3. [Serverless Incident Management System](https://github.com/rawleyc/serverless-incident-manager)** &nbsp; `Jan 2026`

![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=aws-lambda&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazon-dynamodb&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=flat&logo=amazon-aws&logoColor=white)

**Serverless security incident ticketing system to improve SOC response coordination.**

- 🏗️ **Architecture:** Designed a cost-efficient, event-driven microservices architecture that scales to zero when idle.
- ⚡ **Backend:** Developed RESTful APIs using **AWS Lambda (Python/Boto3)** and **API Gateway**.
- 🔔 **Event-Driven:** Enabled automated incident creation to streamline SOC team coordination.
- 📉 **Efficiency:** Reduced infrastructure overhead while maintaining scalable incident handling.

---

## 🛠️ Skills & Technologies

<table>
<tr>
<td valign="top" width="33%">

### 🔍 Security Operations
- Incident Triage & Escalation
- Threat Detection & Log Analysis
- Root Cause Analysis
- TCP/IP & DNS Traffic Analysis
- Port Analysis (53, 88)
- Authentication Protocols (Kerberos, LDAP)

</td>
<td valign="top" width="34%">

### ☁️ Cloud Security
- AWS (EC2, IAM, VPC, Lambda)
- CloudTrail Audit Logging
- IAM Policy Enforcement
- Identity Federation Concepts
- S3 & DynamoDB
- VPC, Route53, API Gateway

</td>
<td valign="top" width="33%">

### 🧰 Platforms & Tooling
- **SIEM:** Splunk · IBM QRadar
- **Network:** Wireshark
- **Monitoring:** AWS CloudTrail · GuardDuty
- **Identity:** Active Directory · Group Policy
- **Scripting:** Python (Boto3) · Bash · PowerShell
- **DevOps:** Git · GitHub · Jenkins

</td>
</tr>
</table>

---

## 💼 Experience

### **Mine Vaganti NGO** — *Project Management & IT Support*
**Jul 2025 – Sep 2025**

- 🔐 Administered **Active Directory** environments including Organizational Units and Group Policy Objects.
- ☁️ Supported **Microsoft 365** infrastructure and user authentication issues.
- 🎫 Resolved service desk incidents via ticketing systems while maintaining **SLA targets**.
- 📄 Documented troubleshooting procedures to improve response consistency.

### **InPost S.A.** — *Logistics Operations Coordinator*
**Nov 2024 – Jun 2025**

- 🌐 Diagnosed workstation and **TCP/IP connectivity** issues in a high-volume operational environment.
- 🔍 Investigated recurring system incidents affecting warehouse management systems.
- 🚨 Acted as **first-response technical contact** for operational IT disruptions.

---

## 📚 Training & Continuous Learning

### **TryHackMe** — [Top 1% Global Rank](https://tryhackme.com/p/DartMouthWrld)

![TryHackMe Top 1%](https://img.shields.io/badge/Rank-Top_1%25_Globally-success?style=flat&logo=tryhackme&logoColor=white)
![Rooms Completed](https://img.shields.io/badge/Rooms_Completed-125%2B-blue?style=flat&logo=tryhackme&logoColor=white)

**Completed Learning Paths:**
- ✅ Pre-Security
- ✅ Cyber Security 101
- ✅ SOC Level 1

**Focus Areas:**
- Cloud Security (AWS Identity, S3 Security)
- Defensive Security (SIEM, Log Analysis, Incident Response)
- Network Security (Nmap, Wireshark, Protocol Analysis)

---

## 🎓 Education & Certifications

| | Credential | Status |
|---|---|---|
| 🔴 | **CompTIA Security+ Certified** | ✅ Active |
| 🟢 | **ISC² Certified in Cybersecurity (CC)** | ✅ Active |
| 🟣 | **TryHackMe Security Analyst (SAL1)** | ✅ Certified |
| 🎓 | **B.Sc. Computer Science** — Lubelska Akademia WSEI | 📖 2024 – Present |

---

<details>
<summary><strong>📖 More About Me</strong></summary>
<br/>

I'm a Security-focused IT professional who bridges the gap between **Cybersecurity Operations** and **Cloud Engineering**. My trajectory is intentional: building deep expertise in threat detection and incident response while architecting automated security solutions in the cloud — converging at **DevSecOps**.

**What drives me:**
- Building automated detection and response pipelines that reduce MTTR
- Translating security operations knowledge into cloud-native solutions
- Continuous research and hands-on lab work to stay ahead of emerging threats

**Languages:**
- 🇬🇧 English (Native)
- 🇿🇼 Shona (Native)

</details>

<details>
<summary><strong>💡 Soft Skills & Strengths</strong></summary>
<br/>

- Analytical Thinking & Pattern Recognition
- Structured Incident Escalation
- Attention to Detail in Log Review
- Calm Decision-Making Under Pressure
- Risk Awareness & Security Mindset
- Documentation for Audit & Compliance
- Continuous Threat Research (Self-Learning Driven)

</details>

---

<div align="center">

### 📬 Let's Connect

Open to roles in **SOC Analysis**, **Cloud Security Engineering**, and **Cyber Security**.

[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chirumerawley@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rawleyc)
[![TryHackMe](https://img.shields.io/badge/TryHackMe_Profile-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/DartMouthWrld)

---

*"Security is not a product, but a process." — Bruce Schneier*

</div>
