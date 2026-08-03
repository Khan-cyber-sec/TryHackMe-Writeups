# TryHackMe: Introduction to Defensive Security

## Overview
This room covers the foundational concepts of Defensive Security (Blue Teaming) through a simulated SOC Analyst dashboard workflow, including threat detection, attack investigation, and mitigation.

## Tasks & Workflow

### 1. Defensive Security Mindset
* *Goal:* Continuous monitoring, threat detection, and swift incident response before system damage occurs.
* *Difference:* Unlike Offensive Security (attacking to find vulnerabilities), Defensive Security protects infrastructure and systems.

### 2. Threat Detection & Log Analysis
* *Concept:* Using SIEM dashboards to monitor real-time alerts.
* *Key Finding:* Identified a Web Discovery Attack originating from suspicious *Source IP:* 32.122.195.63.

### 3. Attack Investigation
* *Concept:* Analyzing attacker activity and target endpoints.
* *Key Finding:* Attacker performed automated directory enumeration targeting sensitive admin portals (https://fakebank.com/admin).

### 4. Containment & Remediation
* *Concept:* Implementing security controls to stop ongoing attacks.
* *Action Taken:* Updated Firewall rules to *BLOCK* the malicious IP 32.122.195.63, successfully containing the threat.

## Key Security Tools & Terms
* *SIEM:* Centralized log monitoring and alert management.
* *Firewall:* Network filter used to block or allow traffic based on IP/rules.
* *WAF (Web Application Firewall):* Protects web apps by filtering HTTP/HTTPS traffic.
* *Rate Limiting:* Prevents automated brute-force or enumeration scripts by limiting incoming requests per second.
