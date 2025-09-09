# ⚙️ DevSecOps Tools

DevSecOps integrates **security into DevOps practices**, ensuring security testing, monitoring, and compliance throughout the **CI/CD pipeline**.  
Below are the key tools provided by **AWS, Microsoft Azure, Google Cloud (GCP)**, plus leading **third-party** and **open-source** solutions.  

---

## 🌩️ AWS DevSecOps Tools
- [**AWS CodePipeline**](https://aws.amazon.com/codepipeline/) – CI/CD pipeline with security integrations  
- [**AWS CodeBuild**](https://aws.amazon.com/codebuild/) – Automated build and test with security scanning integration  
- [**AWS Inspector**](https://aws.amazon.com/inspector/) – Automated vulnerability scanning for EC2 and ECR  
- [**AWS Security Hub**](https://aws.amazon.com/security-hub/) – Compliance and vulnerability posture visibility  
- [**AWS CodeGuru**](https://aws.amazon.com/codeguru/) – Automated code reviews and security recommendations  

---

## ☁️ Azure DevSecOps Tools
- [**Azure DevOps**](https://azure.microsoft.com/en-us/services/devops/) – CI/CD with built-in security extensions  
- [**GitHub Advanced Security**](https://docs.github.com/en/code-security) – Code scanning, secret scanning, and dependency alerts  
- [**Microsoft Defender for DevOps**](https://learn.microsoft.com/en-us/azure/defender-for-devops/overview) – Security for multi-pipeline CI/CD (GitHub, Azure DevOps, Jenkins)  
- [**Azure Policy**](https://learn.microsoft.com/en-us/azure/governance/policy/overview) – Enforce security guardrails in CI/CD  
- [**Azure Key Vault**](https://azure.microsoft.com/en-us/services/key-vault/) – Secure secrets management for pipelines  

---

## 🌐 GCP DevSecOps Tools
- [**Cloud Build**](https://cloud.google.com/build) – CI/CD pipeline service with security scanning integration  
- [**Binary Authorization**](https://cloud.google.com/binary-authorization) – Enforce container image security policies before deployment  
- [**Container Analysis**](https://cloud.google.com/container-analysis) – Vulnerability scanning for container images in Artifact Registry  
- [**Cloud Deploy**](https://cloud.google.com/deploy) – Secure release pipeline for Kubernetes applications  
- [**Forseti Security**](https://forsetisecurity.org) – Open-source tool for enforcing policies in GCP environments  

---

## 🛠️ Third-Party DevSecOps Tools
- [**Snyk**](https://snyk.io) – Developer-first security for open-source, containers, and IaC  
- [**Checkmarx**](https://checkmarx.com) – Static application security testing (SAST) for CI/CD  
- [**Veracode**](https://www.veracode.com) – Application security testing platform  
- [**Aqua Security**](https://www.aquasec.com) – Container and Kubernetes runtime protection  
- [**Palo Alto Prisma Cloud**](https://www.paloaltonetworks.com/prisma/cloud) – Cloud-native application protection platform (CNAPP)  
- [**JFrog Xray**](https://jfrog.com/xray/) – Security scanning of artifacts and dependencies  

---

## 🆓 Open-Source DevSecOps Tools
### 1. Static & Dynamic Analysis
- [**SonarQube**](https://www.sonarqube.org) – Open-source static code analysis (SAST)  
- [**OWASP ZAP (Zed Attack Proxy)**](https://www.zaproxy.org) – DAST tool for web app security testing  
- [**Bandit**](https://bandit.readthedocs.io) – Python security linter for code scanning  

### 2. Dependency & Container Security
- [**Trivy**](https://aquasecurity.github.io/trivy/) – Vulnerability scanner for containers, IaC, and open-source dependencies  
- [**Clair**](https://github.com/quay/clair) – Container vulnerability scanner  
- [**Grype**](https://github.com/anchore/grype) – Vulnerability scanner for container images and filesystems  

### 3. Infrastructure as Code (IaC) Security
- [**Checkov**](https://www.checkov.io) – IaC scanning for Terraform, CloudFormation, Kubernetes  
- [**tfsec**](https://aquasecurity.github.io/tfsec/) – Static analysis for Terraform security misconfigurations  
- [**Kube-bench**](https://github.com/aquasecurity/kube-bench) – CIS benchmark checks for Kubernetes clusters  
- [**Kubesec**](https://kubesec.io) – Security risk analysis for Kubernetes manifests  

### 4. Secrets & Policy Management
- [**HashiCorp Vault**](https://www.vaultproject.io) – Secrets management for DevOps pipelines  
- [**Sealed Secrets (Bitnami)**](https://github.com/bitnami-labs/sealed-secrets) – Encrypt Kubernetes secrets in GitOps workflows  
- [**OPA (Open Policy Agent)**](https://www.openpolicyagent.org) – Policy-as-code engine for CI/CD and Kubernetes  

---

## 📌 Summary
DevSecOps tools embed **security controls into CI/CD pipelines**, ensuring secure code, dependencies, containers, and infrastructure.  
- **Cloud-native tools** (AWS, Azure, GCP) provide baseline integrations.  
- **Third-party tools** add enterprise-grade application and container security.  
- **Open-source tools** empower DevOps teams with **SAST, DAST, IaC scanning, and policy enforcement**.  

