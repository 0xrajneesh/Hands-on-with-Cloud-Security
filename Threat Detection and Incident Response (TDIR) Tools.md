# 🛡️ Threat Detection and Incident Response (TDIR) Tools

Threat Detection and Incident Response (TDIR) involves **identifying, analyzing, and responding to cyber threats** in real-time.  
Below are the key tools provided by **AWS, Microsoft Azure, Google Cloud (GCP)**, plus leading **third-party** and **open-source** solutions.  

---

## 🌩️ AWS TDIR Tools
- [**Amazon GuardDuty**](https://aws.amazon.com/guardduty/) – Threat detection for malicious activity and anomalies  
- [**AWS Security Hub**](https://aws.amazon.com/security-hub/) – Centralized security posture management & alerts  
- [**Amazon Detective**](https://aws.amazon.com/detective/) – Investigates and analyzes security events  
- [**AWS CloudTrail**](https://aws.amazon.com/cloudtrail/) – Audit and log monitoring for suspicious activities  
- [**AWS Incident Manager (Systems Manager)**](https://aws.amazon.com/systems-manager/incident-manager/) – Automated incident response playbooks  
- [**Amazon Macie**](https://aws.amazon.com/macie/) – Data security and sensitive data detection  

---

## ☁️ Azure TDIR Tools
- [**Microsoft Defender for Cloud**](https://azure.microsoft.com/en-us/products/defender-for-cloud/) – Cloud-native workload threat protection  
- [**Microsoft Sentinel**](https://azure.microsoft.com/en-us/products/microsoft-sentinel/) – SIEM + SOAR for threat detection & incident response  
- [**Microsoft 365 Defender**](https://www.microsoft.com/en-us/security/business/microsoft-365-defender) – Threat detection across Microsoft 365 apps  
- [**Azure Monitor & Log Analytics**](https://learn.microsoft.com/en-us/azure/azure-monitor/overview) – Centralized monitoring and alerting  
- [**Microsoft Defender for Identity**](https://www.microsoft.com/en-us/security/business/identity-access/defender-identity) – Detects identity-related attacks  

---

## 🌐 GCP TDIR Tools
- [**Google Chronicle Security Operations**](https://cloud.google.com/chronicle) – SIEM & threat hunting with Google scale  
- [**Security Command Center (SCC)**](https://cloud.google.com/security-command-center) – Threat detection, compliance, and risk visibility  
- [**Google Cloud Logging & Monitoring**](https://cloud.google.com/products/operations) – Observability for incidents and anomalies  
- [**Google Cloud Armor**](https://cloud.google.com/armor) – DDoS protection and threat mitigation  
- [**Event Threat Detection (ETD)**](https://cloud.google.com/security/products/event-threat-detection) – Built-in rule-based threat detection for logs  

---

## 🛠️ Third-Party TDIR Tools
- [**Splunk Enterprise Security**](https://www.splunk.com/en_us/software/enterprise-security.html) – SIEM & threat analytics platform  
- [**IBM QRadar**](https://www.ibm.com/qradar) – SIEM and incident response orchestration  
- [**CrowdStrike Falcon**](https://www.crowdstrike.com) – Endpoint detection & response (EDR) + threat intelligence  
- [**Palo Alto Cortex XDR/XSOAR**](https://www.paloaltonetworks.com/cortex) – Extended detection and automated response  
- [**SentinelOne Singularity**](https://www.sentinelone.com) – AI-driven EDR and incident response platform  
- [**FireEye Helix (Trellix)**](https://www.trellix.com) – Threat detection & IR automation  

---

## 🆓 Open-Source TDIR Tools
### 1. Cloud Security Posture & Monitoring
- [**Cloud Custodian**](https://cloudcustodian.io) – Policy-as-code tool for managing security, compliance, and governance in AWS, Azure, and GCP  
- [**Prowler**](https://github.com/prowler-cloud/prowler) – Multi-cloud security auditing, CIS benchmarks, and incident readiness checks  
- [**ScoutSuite**](https://github.com/nccgroup/ScoutSuite) – Multi-cloud auditing tool for threat exposure and misconfigurations  
- [**CloudSploit (by Aqua)**](https://github.com/aquasecurity/cloudsploit) – Open-source scanning of AWS, Azure, and GCP for misconfigurations  

---

### 2. Threat Detection & Hunting
- [**Wazuh**](https://wazuh.com) – Open-source SIEM/XDR with integrations for AWS CloudTrail, Azure Activity Logs, and GCP Audit Logs  
- [**Falco**](https://falco.org) – CNCF project for runtime threat detection in Kubernetes and containers  
- [**Zeek**](https://zeek.org) – Network security monitoring, useful for cloud and hybrid workloads  
- [**Suricata**](https://suricata.io) – IDS/IPS engine for detecting malicious cloud network activity  

---

### 3. Incident Response & Case Management
- [**TheHive**](https://thehive-project.org) – Open-source incident response platform (IRP) with case management  
- [**Cortex**](https://www.cortex-ia.org) – Automates observable analysis and response actions (integrates with TheHive)  
- [**DFIR-IRIS**](https://dfir-iris.org) – IR platform for DFIR teams with case tracking and workflow automation  

---

### 4. Cloud Forensics & Investigation
- [**Cloud Forensics Framework (CFF)**](https://github.com/google/cloud-forensics-utils) – Google’s DFIR toolkit for GCP, AWS, and Azure  
- [**AWS IR Toolkit**](https://github.com/ThreatResponse/aws_ir) – Scripts for incident response and forensics in AWS  
- [**Cloud Incident Response (CIRT) Tools**](https://github.com/forensicanalysis/forensicanalysis) – Modular cloud incident response and forensic utilities  
- [**OSQuery**](https://osquery.io) – SQL-powered endpoint detection and investigation (extendable to cloud workloads)  



## 📌 Summary
TDIR tools combine **threat detection, alerting, investigation, and automated incident response**.  
- **Cloud-native tools** (AWS, Azure, GCP) provide built-in threat visibility.  
- **Third-party platforms** enhance enterprise-scale detection & orchestration.  
- **Open-source tools** give flexibility for SOCs, MSSPs, and labs.  

