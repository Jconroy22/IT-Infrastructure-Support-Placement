# Enterprise IT Infrastructure & Support Placement

![Platform](https://img.shields.io/badge/OS-Windows%2011%20%7C%20Active%20Directory-blue)
![Focus](https://img.shields.io/badge/Focus-Infrastructure%20%26%20Asset%20Management-green)
![Compliance](https://img.shields.io/badge/Security-NIST%20%7C%20GDPR%20Compliant-orange)

## Introduction

Welcome to the documentation repository for my 12-week Work-Based Learning placement as an **IT Support Technician** at a large Further & Higher Education Institution in the UK.

During this placement, I was integrated into the central IT Support team, operating across a large-scale, multi-campus educational estate. The role encompassed maintaining Windows 11 endpoints, Active Directory environments, network switch handshakes, specialized AV equipment, and automated print fleets.

This repository serves as a portfolio of my hands-on technical work, detailing enterprise network troubleshooting, endpoint incident response, hardware component repairs, and asset management audits executed during the placement.

> **Privacy & Compliance Note:** In accordance with institutional non-disclosure policies, GDPR, and UK Data Protection legislation, all specific room numbers, server hostnames, internal IP ranges, and organizational identifiers have been anonymized.

---

## Featured Major Project: Campus-Wide Laptop Battery & Infrastructure Audit

* **Scope:** Multi-campus fleet | 80+ endpoints | Mobile Charging Infrastructure  
* **Role:** Lead Technician for Audit & Remediation  

### Problem Statement
Degraded laptop batteries and misconfigured charging trolleys were causing frequent mid-class device failures across multiple academic departments, leading to heavy daily support ticket volume and disrupted learning environments.

### Execution & Technical Methodology
* **Comprehensive Health Audit:** Systematically documented cycle counts, battery capacity vs. design capacity, and physical degradation across mobile trolleys deployed in various computer labs and specialized study suites.
* **Infrastructure Remediation:** Identified a critical systemic fault where Power Distribution Unit (PDU) timers were misconfigured. Recalibrated PDUs to safe 2-hour cycles to prevent overcharging, severe battery swelling, and thermal degradation.
* **Asset Tracking System:** Solved a persistent operational bottleneck where devices were mixed across three separate trolleys by designing and implementing a standardized labeling and attribution system for senior management approval.

### Impact & Outcomes
* **Cost Prevention:** Extended asset lifecycle for 80+ endpoints, preventing premature battery replacements and hardware write-offs.
* **Ticket Reduction:** Significantly reduced daily emergency support tickets related to dead classroom laptops.
* **Process Improvement:** Established a standardized reporting template adopted by the team for ongoing preventative maintenance.

---

## Additional Infrastructure & Support Deliverables

* **Fleet-Wide Network Remediation:** Executed CLI commands (`gpupdate /force`, `ipconfig /flushdns`) across 300+ laptops across 19 mobile trolleys to restore Domain Controller authentication following core switch firmware updates.
* **Cybersecurity Incident Response:** Physically isolated compromised lab endpoints following Trojan alerts and executed pre-boot **Windows Defender Offline scans** to eradicate persistent threats following NIST containment principles.
* **Component Repairs & Security Controls:** Performed laptop motherboard replacements, managing TPM security triggers, BitLocker recovery key retrieval via Active Directory, and vendor liaison for BIOS master keys.

---

## Diagnostic CLI Snippets Used

```cmd
:: Force immediate Group Policy Object refresh with Domain Controller
gpupdate /force

:: Flush DNS resolver cache to fix network resolution failures
ipconfig /flushdns

:: Verify local network adapter configuration and IP allocation
ipconfig /all
