# Martel Baldwin | Cybersecurity Portfolio

## About Me

Operations professional with over 12 years of experience managing teams, scheduling, and coordinating complex processes in high-pressure environments, currently transitioning into cybersecurity through the Google Cybersecurity Professional Certificate.

The transition connects directly to what drove my growth at FedEx. I asked to learn systems beyond the assigned role, from yard equipment to billing audits, until I was trusted to work anywhere in the building. That same curiosity is pointing me toward cybersecurity now.

## Technical Skills

- NIST Cybersecurity Framework (CSF)
- Google Workspace, Salesforce, SAP Business Objects
- Security auditing, risk assessment, compliance, access controls, incident response
- Google Project Management Professional Certificate (2023)
- Google Cybersecurity Professional Certificate (in progress)

## Google Cybersecurity Certificate Projects

### Project 1: Botium Toys Internal Security Audit

**Description**
Conducted an internal security audit for a fictional U.S. toy company. Reviewed the company's assets, risks, and current security posture, then completed a controls and compliance checklist using the NIST Cybersecurity Framework.

**Supporting Documents**
- [Botium Toys Risk Assessment](Botium%20Toys%20risk%20assessment.pdf)
- [Controls and Compliance Checklist](Controls%20and%20compliance%20checklist.pdf)

**Key Findings**
- Multiple critical gaps identified around payment processing, data protection, and access controls
- Deficiencies in credit card data handling, encryption, least privilege access, separation of duties, disaster recovery, backups, and privacy policies

**Recommendations**
- Implement strong encryption for all credit card data at rest and in transit
- Enforce least privilege access and separation of duties for systems handling sensitive customer data
- Develop formal data privacy policies and procedures, including PII/SPII and EU compliance
- Establish regular backup processes and a tested disaster recovery plan
- Deploy intrusion detection and prevention systems and conduct ongoing security awareness training

**My Approach**
Looking through the risk assessment, the first thing I noticed was that every employee had full access to cardholder data and customer PII with no restrictions. That creates real accountability problems.

From there I worked through the checklist based on what was actually enforced versus what just existed on paper. The password policy was okay but nobody was following it because there was nobody telling them what to do. Same thing with the legacy systems and a few other controls. Not much was really enforced.

The physical security was the strongest area. Locks, CCTV, fire detection, all of it was confirmed and functioning.

The most urgent fixes were encrypting the credit card data and restricting access based on job function.

**Skills Applied**
Internal security auditing, control gap analysis, NIST Cybersecurity Framework, compliance assessment, risk identification and remediation planning

**Status**
Completed, Google Cybersecurity Professional Certificate, Course 1

---

### Project 2: NIST CSF Incident Response Exercise

**Description**
A multimedia company offering web design, graphic design, and social media marketing experienced a DoS attack that took down their internal network for two hours. A threat actor sent a flood of ICMP pings through an unconfigured firewall, preventing all internal network traffic from accessing any network resources. The incident management team responded by blocking incoming ICMP packets, taking non-critical services offline, and restoring critical services. Using the NIST Cybersecurity Framework, this exercise involved analyzing the incident across all five CSF functions and developing an improvement plan.

**Supporting Documents**
- [Incident Report Analysis](Incident%20report%20analysis.pdf)

**Incident Analysis**

**Identify**
A malicious actor targeted the company with an ICMP flood attack through an unconfigured firewall. The entire internal network was affected and all critical network resources needed to be secured and restored.

**Protect**
A new firewall rule was implemented to limit the rate of incoming ICMP packets. An IDS/IPS system was put in place to filter ICMP traffic based on suspicious characteristics.

**Detect**
Source IP address verification was configured on the firewall to check for spoofed IP addresses. Network monitoring software was installed to detect abnormal traffic patterns in real time.

**Respond**
The team blocked incoming ICMP packets and took non-critical network services offline to reduce internal traffic while critical services were restored. For future incidents, the response plan includes isolating affected systems, restoring critical services first, analyzing network logs for suspicious activity, and reporting to management and legal authorities if applicable.

**Recover**
External ICMP flood attacks can be blocked at the firewall. Non-critical services should be stopped first to reduce internal network traffic, then critical services restored. Once the ICMP flood times out, non-critical systems can be brought back online.

**Skills Applied**
NIST Cybersecurity Framework, incident response analysis, network security, DoS attack identification, firewall configuration concepts, IDS/IPS systems

**Status**
Completed, Google Cybersecurity Professional Certificate, Course 3

## In Progress

**Project 3: Tools of the Trade: Linux and SQL**
Currently completing Course 4 of the Google Cybersecurity Professional Certificate, focusing on Linux command line and SQL for cybersecurity applications.

## Contact
- LinkedIn: linkedin.com/in/martel-baldwin-35081a240
- Email: martellorenzo@aol.com
