Survey of **governance**, **security** and **compliance tooling** for cloud-native environments.

---

| **Feature**                 | **Description**                                                                                              | **Examples of Tools**                                                                                          | **Relevance/Details**                                                                                                                                                                                                                               |
|-----------------------------|----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Container Security**      | Scanning and protecting container images and runtimes to identify vulnerabilities and prevent exploits.    | - **Aqua Security**, **Sysdig Secure**, **Palo Alto Prisma Cloud**, **Twistlock**                             | Full-lifecycle container protection including vulnerability scanning, runtime protection, and compliance enforcement.                                                                                                                             |
| **Kubernetes Security**     | Securing Kubernetes environments through policy enforcement, auditing, and monitoring.                    | - **Kubernetes Policy Controller**, **Kyverno**, **OPA/Gatekeeper**, **StackRox**                             | Enables role-based access control (RBAC), admission control, runtime anomaly detection, and secure cluster configurations.                                                                                                                       |
| **Network Security**        | Securing cloud-native network traffic with advanced segmentation, monitoring, and threat detection.       | - **Cilium (with Tetragon)**, **Calico Enterprise**, **Zscaler Cloud Security**, **F5 Distributed Cloud**       | Tailored for security, these tools provide east-west traffic inspection, secure microsegmentation, and advanced threat protection for Kubernetes and cloud-native apps.                                                                            |
| **Governance and Policy Enforcement** | Ensuring consistent policy enforcement across cloud environments, including cost, security, and resource controls.  | - **OPA (Open Policy Agent)**, **Cortex Governance**, **AWS Organizations**, **Google Assured Workloads**      | Policy as Code frameworks like OPA allow centralized, version-controlled policy enforcement. Governance solutions ensure compliance with organizational mandates.                                                                                  |
| **Compliance Automation**   | Automating audits and assessments for frameworks like GDPR, PCI DSS, HIPAA, and SOC 2.                   | - **AWS Audit Manager**, **Azure Security Center**, **Drata**, **Vanta**, **Lacework**                        | These tools continuously assess cloud resources against regulatory requirements, generate audit-ready reports, and provide remediation steps.                                                                                                     |
| **API Security**            | Securing APIs from threats like injection, DDoS, and sensitive data leaks.                               | - **Salt Security**, **Traceable AI**, **42Crunch**, **Imperva API Security**                                 | Advanced tools for API-specific vulnerabilities, focusing on runtime protection, traffic analysis, and integration into development processes.                                                                                                     |
| **Cloud Security Posture Management (CSPM)** | Ensuring secure configurations of cloud-native resources and compliance with best practices.                          | - **Palo Alto Prisma Cloud**, **Wiz**, **Orca Security**, **AWS Security Hub**, **Check Point CloudGuard**     | CSPM tools detect misconfigurations, enforce security best practices, and provide unified dashboards for multi-cloud environments.                                                                                                                |
| **Threat Detection and Incident Response** | Real-time detection and mitigation of threats targeting cloud-native workloads.                                | - **Datadog Security Monitoring**, **Falco**, **CrowdStrike Falcon**, **Microsoft Defender for Cloud**         | These tools provide threat intelligence, anomaly detection, and automated incident response tailored to containerized and serverless environments.                                                                                                |
| **Identity and Access Management (IAM) Governance** | Enforcing least privilege and monitoring IAM configurations to prevent privilege escalation or over-permissive roles. | - **IAM Access Analyzer**, **CyberArk Conjur**, **Okta Workflows**, **Symmetry Systems DataGuard**             | Focuses on detecting and mitigating over-permissions, misconfigured identities, and privilege escalation risks, with tools supporting cloud-native IAM complexity.                                                                                |
| **Data Security and Encryption** | Protecting sensitive data at rest, in transit, and during use with encryption and access policies.                        | - **HashiCorp Vault**, **AWS KMS**, **Google Cloud KMS**, **Thales CipherTrust**                               | Centralized key management, policy enforcement for data encryption, and secure secret storage ensure data security across distributed systems.                                                                                                     |
| **Observability for Security** | Collecting and analyzing logs, metrics, and traces for security-focused insights and anomaly detection.                    | - **Splunk Observability Cloud**, **Elastic Security**, **New Relic Lookout**, **Prometheus + Grafana Loki**   | Focuses on integrating observability data with security tools to quickly detect, trace, and respond to security incidents.                                                                                                                        |
| **Software Supply Chain Security** | Securing code dependencies, CI/CD pipelines, and artifact repositories to prevent compromise.                          | - **Snyk**, **JFrog Xray**, **Sonatype Nexus IQ**, **Sigstore**                                               | Ensures code integrity by scanning for vulnerabilities in dependencies, verifying artifact authenticity, and securing the CI/CD workflow.                                                                                                         |
| **Configuration and IaC Security** | Scanning and securing IaC templates for misconfigurations before deployment.                                            | - **Bridgecrew**, **Terraform Sentinel**, **Checkov**, **Pulumi CrossGuard**                                  | Prevents deployment of insecure cloud resources by validating Terraform, CloudFormation, and other IaC templates against security best practices.                                                                                                |
| **Governance Dashboards and Reporting** | Providing executive-level views of security posture and compliance across the cloud environment.                    | - **AWS Well-Architected Tool**, **CloudHealth by VMware**, **RedLock (Palo Alto)**                            | Enables centralized reporting of compliance and governance, providing actionable insights to executives and security teams.                                                                                                                        |

---

### **Key Trends in Cloud-Native Security, Compliance, and Governance:**
1. **Convergence of Tools**: Solutions like **Prisma Cloud** and **Wiz** provide unified security for the full lifecycle (code, runtime, compliance).
2. **Focus on Policy as Code**: Tools like **OPA** are becoming essential for enforcing consistent security and governance policies.
3. **Shift Toward Zero Trust**: Increased adoption of zero-trust models for securing workloads, APIs, and network communications.
4. **Real-Time Compliance**: Automated compliance checks are critical to keep pace with the speed of cloud-native development.

This updated list better reflects the specialized tools available for cloud-native **security**, **compliance**, and **governance**, and highlights their tailored purposes.


## Tooling Overview

Here are some tools and platforms that offer features aligning with the outlined pillars and functionality of OpsCanvas:

---

### **Visibility**
Tools focused on providing situational awareness, monitoring, and cloud management:  
1. **Datadog**  
   - Comprehensive cloud and application monitoring.
   - DORA metrics tracking (customizable dashboards).  
   - Cost analysis integrations for AWS.
2. **AWS Cost Explorer**  
   - Insights into cloud cost allocation and optimization.  
3. **New Relic**  
   - Performance monitoring and deployment tracking.
   - Cloud resource and app usage visibility.
4. **Splunk**  
   - Action auditing and error tracking in logs.
   - Cloud insights and reporting.
5. **Honeycomb.io**  
   - Observability for applications and distributed systems.
   - Supports tracing and deployment monitoring.

---

### **Compliance**
Tools focused on regulatory compliance, operational excellence, and vulnerability scanning:  
1. **AWS Security Hub**  
   - Centralized security and compliance checks for AWS environments.  
2. **Checkov**  
   - Infrastructure-as-Code (IaC) compliance and security checks.  
3. **Prisma Cloud** (by Palo Alto Networks)  
   - Supply chain, access control, and policy compliance.  
4. **SonarQube**  
   - Code quality and vulnerability analysis.  
5. **Jira Align / Atlassian tools**  
   - Policy and performance reporting for compliance.  

---

### **Governance**
Tools providing policy enforcement, cost governance, and workflow standardization:  
1. **HashiCorp Sentinel**  
   - Policy-as-code enforcement for infrastructure automation workflows.  
2. **CloudHealth by VMware**  
   - Cloud cost management and governance.  
3. **Terraform Cloud**  
   - Governance for infrastructure-as-code pipelines.
4. **Open Policy Agent (OPA)**  
   - Policy enforcement in Kubernetes and IaC.

---

### **Control**
Tools enabling development and operational control for ICs:  
1. **Terraform** (HashiCorp)  
   - Trusted IaC with lifecycle and environment management.  
2. **Pulumi**  
   - Modern IaC tool with environment promotion capabilities.  
3. **ArgoCD**  
   - GitOps-based application deployment and management.  
4. **Kubernetes**  
   - Supports ephemeral environments and environment promotion.
5. **AWS CloudFormation**  
   - AWS-native IaC and automation tool.  

---

### **Pipeline Runners**
Tools for CI/CD pipeline automation and governance:  
1. **GitLab CI/CD**  
   - Governance controls and custom runner options.  
2. **GitHub Actions**  
   - Flexible workflows for CI/CD with IaC compatibility.
3. **Jenkins**  
   - Highly customizable with governance plugins.  
4. **CircleCI**  
   - Quick pipeline setup with governance controls.  

---

### **OC CLI**
CLI tools providing standardized workflows for developers and DevOps practitioners:  
1. **AWS CLI**  
   - Full control over AWS services via the terminal.  
2. **HashiCorp Terraform CLI**  
   - Provisioning and management of cloud resources.  
3. **Pulumi CLI**  
   - IaC resource creation with modern scripting.
4. **kubectl**  
   - Kubernetes management from the command line.  

---

### **Web Portal**
Platforms with centralized dashboards for governance, monitoring, and reporting:  
1. **ServiceNow**  
   - Incident and policy management with a focus on compliance.  
2. **AWS Management Console**  
   - Central hub for AWS governance and reporting.  
3. **Grafana**  
   - Data visualization and alert management.  
4. **Atlassian Confluence**  
   - Centralized reporting and documentation tool.  

These tools collectively cover most of the features described for OpsCanvas Plus, ranging from visibility and governance to pipeline management and CLI interfaces.

## Tooling Details

Here’s an in-depth look at the listed tools, categorized by their focus areas and functionality:

---

## **Visibility**

### **1. Datadog**
- **Description:** A comprehensive observability platform for modern applications and cloud infrastructure.
- **Features:**
  - **Cloud and Application Monitoring:** Tracks application performance, logs, metrics, and traces to provide end-to-end visibility.
  - **DORA Metrics:** Offers pre-built dashboards for tracking metrics like deployment frequency, change failure rate, lead time for changes, and MTTR.
  - **Cost Analysis:** Integrates with AWS Cost Explorer to monitor and analyze cloud costs, with customizable cost dashboards.

---

### **2. AWS Cost Explorer**
- **Description:** A native AWS tool for analyzing and managing cloud expenses.
- **Features:**
  - Provides insights into historical spending patterns, enabling users to identify trends and forecast future costs.
  - Supports the creation of custom cost allocation reports by tagging resources.
  - Identifies unused or underutilized resources to optimize spending.

---

### **3. New Relic**
- **Description:** A performance monitoring platform for applications and infrastructure.
- **Features:**
  - **Performance Monitoring:** Tracks application health, errors, and response times in real time.
  - **Cloud Resource Usage:** Monitors cloud infrastructure and provides insights into resource utilization and optimization opportunities.
  - **Deployment Tracking:** Analyzes deployment events and correlates them with performance changes.

---

### **4. Splunk**
- **Description:** A data analytics and monitoring platform for IT operations and security.
- **Features:**
  - **Log Management:** Collects, indexes, and analyzes log data from cloud applications and infrastructure.
  - **Action Auditing:** Tracks user activities, changes, and error events for improved accountability.
  - **Cloud Insights:** Offers customizable dashboards for visualizing cloud performance and usage metrics.

---

### **5. Honeycomb.io**
- **Description:** An observability platform focused on distributed systems.
- **Features:**
  - **Tracing:** Supports end-to-end tracing to identify bottlenecks and diagnose performance issues in microservices.
  - **Deployment Monitoring:** Monitors deployment impacts and provides instant insights into production changes.
  - **Query-Driven Debugging:** Allows deep exploration of operational data to uncover issues quickly.

---

## **Compliance**

### **1. AWS Security Hub**
- **Description:** A security and compliance management service for AWS environments.
- **Features:**
  - Aggregates and prioritizes security findings from AWS services and third-party tools.
  - Checks for compliance against standards like CIS benchmarks, GDPR, and PCI DSS.
  - Provides automated alerts and remediation recommendations for identified vulnerabilities.

---

### **2. Checkov**
- **Description:** An open-source tool for static analysis of Infrastructure-as-Code (IaC).
- **Features:**
  - Scans Terraform, CloudFormation, Kubernetes, and other IaC files for misconfigurations.
  - Provides compliance checks against security benchmarks like CIS and NIST.
  - Integrates with CI/CD pipelines to enforce security early in the development lifecycle.

---

### **3. Prisma Cloud (by Palo Alto Networks)**
- **Description:** A cloud security platform with capabilities across multiple cloud environments.
- **Features:**
  - **Supply Chain Security:** Analyzes software supply chain vulnerabilities and misconfigurations.
  - **Access Control:** Enforces identity and access policies for cloud users and applications.
  - **Policy Compliance:** Provides reports and alerts for compliance with regulatory standards.

---

### **4. SonarQube**
- **Description:** A platform for code quality and security analysis.
- **Features:**
  - **Code Quality Checks:** Evaluates code for bugs, vulnerabilities, and code smells.
  - **Security Scanning:** Identifies security risks in codebases, including OWASP Top 10 vulnerabilities.
  - **Compliance Reporting:** Ensures code adheres to internal and external quality standards.

---

### **5. Jira Align / Atlassian Tools**
- **Description:** Enterprise planning and tracking tools for software development.
- **Features:**
  - Aligns engineering activities with business objectives for improved compliance.
  - Provides detailed reporting on performance metrics and policy adherence.
  - Integrates with CI/CD tools to ensure visibility into development processes.

---

## **Governance**

### **1. HashiCorp Sentinel**
- **Description:** A policy-as-code framework for enforcing governance in infrastructure automation.
- **Features:**
  - Defines policies as code to ensure infrastructure changes comply with organizational standards.
  - Integrates seamlessly with Terraform and other HashiCorp tools.
  - Supports policy versioning and testing for continuous compliance.

---

### **2. CloudHealth by VMware**
- **Description:** A cloud management platform focusing on cost and governance.
- **Features:**
  - Tracks cloud costs across multiple accounts and regions.
  - Provides governance rules to ensure resource tagging and usage compliance.
  - Suggests optimizations for reducing cloud spend and improving resource efficiency.

---

### **3. Terraform Cloud**
- **Description:** A cloud-based service for managing Terraform workflows.
- **Features:**
  - Provides governance controls for IaC pipelines, such as policy checks with Sentinel.
  - Supports multi-user collaboration with role-based access controls.
  - Automates infrastructure deployment and management with integrated VCS support.

---

### **4. Open Policy Agent (OPA)**
- **Description:** A policy engine for enforcing fine-grained policies in Kubernetes and other environments.
- **Features:**
  - Enforces policies on Kubernetes resources, API requests, and IaC configurations.
  - Provides policy decision logging and auditing.
  - Allows writing custom policies using a declarative language (Rego).

---

Each tool is tailored to address specific pain points in DevOps practices, from monitoring and compliance to governance and automation. These tools can be used individually or integrated into a cohesive DevOps strategy.
