
# Network Security and Protocols

An academic project exploring network security fundamentals, common cyber threats, security protocols, risk assessment, and the development of organizational security policies.

## Project Overview

This project was completed as part of **INT 304: Network Security and Protocols**. It explores the principles and practices used to protect network infrastructure, secure communications, identify vulnerabilities, assess cybersecurity risks, and develop policies for managing security incidents.

The project combines theoretical research, hypothetical organizational case studies, policy development, and a hands-on examination of an HTTPS website's TLS certificate.

## Objectives

- Understand fundamental network security concepts.
- Identify common network attacks, threats, and vulnerabilities.
- Explain the functions and applications of security protocols.
- Examine the importance of HTTPS and TLS certificates in secure communications.
- Conduct a risk assessment for a hypothetical healthcare organization.
- Develop security policies based on identified risks.
- Understand how security policies can be reviewed and adapted to evolving threats.

## Project Contents

### Lab 1: Introduction to Network Security Concepts

This lab examines common network attacks, their potential impact, attack methods, and preventive measures.

Topics covered include:

- Denial of Service (DoS) and Distributed Denial of Service (DDoS)
- Man-in-the-Middle (MitM) attacks
- Phishing and social engineering
- Address Resolution Protocol (ARP) spoofing
- DNS spoofing and cache poisoning
- Packet sniffing and eavesdropping
- SQL injection
- Password attacks
- Zero-day exploits
- Session hijacking

The lab also includes a hypothetical security assessment of an online airtime, data, and utility payment platform, focusing on potential threats to customer information, payment systems, authentication, and APIs.

### Security Protocols

The project reviews key protocols used to protect network communications.

- **TLS (Transport Layer Security):** Protects data in transit through encryption, authentication, and integrity mechanisms.
- **HTTPS (Hypertext Transfer Protocol Secure):** Uses TLS to protect communications between web browsers and servers.
- **IPsec (Internet Protocol Security):** Provides security mechanisms for IP communications and VPN connections.
- **SSH (Secure Shell):** Enables secure remote administration and encrypted communication with remote systems.

The discussion explains how these protocols work and where they may be applied in organizational networks.

### Hands-On Activity: HTTPS/TLS Certificate Inspection

The practical activity involved visiting [Wikipedia](https://www.wikipedia.org) and examining the website's HTTPS certificate information.

The assignment documented:

- Certificate issuer
- Certificate subject
- Certificate validity period
- Encryption-related information
- The importance of certificate validation and secure browsing

This exercise demonstrates the role of TLS certificates in website authentication and the protection of data transmitted between a browser and a web server.

> **Note:** The certificate details recorded in the original assignment reflect the inspection performed at that time and do not represent the website's current certificate configuration.

### Lab 2: Network Security Policies and Risk Management

This lab explores the role of security policies in protecting organizational systems, data, and users.

Policies examined include:

- Acceptable Use Policy
- Access Control Policy
- Password Policy
- Data Classification and Handling Policy
- Email Security Policy
- Mobile Device and Bring Your Own Device (BYOD) Policy
- Remote Access Policy
- Network Security Policy
- Incident Response Policy
- Patch Management Policy
- Backup and Disaster Recovery Policy
- Monitoring and Logging Policy
- Wireless Network Policy

Each policy is considered in terms of its purpose, scope, user responsibilities, incident response considerations, and compliance requirements.

### Risk Assessment: SecureCare Hospital

A hypothetical healthcare provider, SecureCare Hospital, was used to demonstrate a structured cybersecurity risk assessment.

#### Assets Identified

- Electronic Health Records (EHR)
- Patient Personally Identifiable Information (PII)
- Medical devices, including IoT-enabled monitors
- Billing and insurance systems
- Hospital network infrastructure
- Staff access credentials

#### Threats and Vulnerabilities Examined

- Ransomware and malware
- Phishing and credential compromise
- Unauthorized access to medical devices
- SQL injection
- Misconfigured firewalls
- Outdated software
- Weak authentication and missing multi-factor authentication
- Insufficient network segmentation

The assessment considered the likelihood and potential impact of identified threats and assigned risk ratings to help prioritize mitigation measures.

### Security Policy Development

Based on the SecureCare Hospital risk assessment, the project proposes policies and procedures in four key areas.

1. **Access Control:** Role-based access control, unique user accounts, multi-factor authentication, and periodic access reviews.
2. **Data Protection:** Encryption, data classification, restricted data access, secure backups, and vulnerability management.
3. **Incident Response:** Detection, containment, investigation, eradication, recovery, reporting, and post-incident review.
4. **Security Awareness:** Staff cybersecurity orientation, phishing awareness, refresher training, and incident reporting education.

The project also evaluates the strengths and weaknesses of the proposed policies and discusses the importance of regular reviews, testing, training, and adaptation to emerging threats.

## Key Learning Outcomes

Through this project, I explored:

- The relationship between network threats, vulnerabilities, and security controls.
- How common attacks can affect the confidentiality, integrity, and availability of information.
- The importance of encrypted communications and digital certificates.
- How to identify critical assets and evaluate cybersecurity risks.
- How risk assessment findings can inform organizational security policies.
- The role of incident response, access control, employee awareness, and continuous improvement in security management.

## Tools and Resources

The documented practical activity involved a web browser and the public website [Wikipedia](https://www.wikipedia.org) for HTTPS/TLS certificate inspection.

The broader project focused on security concepts, protocols, threat analysis, risk assessment, and policy development.

*This repository documents the academic work described in the assignment. It does not claim that a full vulnerability scan, penetration test, or live attack simulation was performed.*

## Ethical Considerations

The practical activity was limited to reviewing publicly available website certificate information. The online payment platform and healthcare provider used in the risk assessment are presented as case-study scenarios for educational analysis.

Security testing should only be performed on systems for which appropriate authorization has been obtained.

## Conclusion

Network security requires a combination of secure communication protocols, effective access controls, risk management, user awareness, and incident response planning.

This project demonstrates how foundational network security concepts can be applied to hypothetical organizational environments to identify risks, propose appropriate controls, and support the protection of sensitive information and critical services.

## Project Information

- **Course:** INT 304 – Network Security and Protocols
- **Assignment:** Introduction to Network Security Protocols
- **Project Type:** Academic coursework and security analysis
- **Submission Date:** 11 June 2025

## Disclaimer

This repository is intended for educational and portfolio purposes. The case studies and proposed security policies are academic exercises, not independent security audits or verified assessments of the named online platform or hypothetical healthcare organization.
