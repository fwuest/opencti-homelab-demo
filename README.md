# opencti-homelab-demo
This repository will contain demos and configurations for OpenCTI by Filigran

# CSIRT DEMO Case

## FICTIONAL CASE - Security Incident - 2024-02-15 - The Silent Surge - FICTIONAL CASE

The Silent Surge was a targeted cyber espionage campaign against Suefin Data Solutions, a Swiss data analytics company. The attackers, leveraging an Advanced Persistent Threat (APT) approach, initiated the campaign with a sophisticated spear-phishing email aimed at a key employee, Waltor Suefin. This email included a malicious link that, when clicked, installed a Remote Monitoring and Management (RMM) tool, ConnectWise Control (formerly known as ScreenConnect). The RMM tool provided the attackers with a foothold in Suefin's network, enabling stealthy remote access.

Upon establishing initial access, the threat actors deployed a custom-built malicious file designed to escalate privileges and evade detection. The attackers then conducted lateral movement across the network, leveraging stolen credentials and exploiting vulnerabilities. Notably, they targeted Kubernetes environments and Linux systems running Red Hat Enterprise Linux (RHEL).

Key vulnerabilities exploited during the attack included CVE-2022-0847 (Dirty Pipe), CVE-2022-0185, and Kubernetes vulnerabilities such as CVE-2023-2728. The attackers demonstrated a deep understanding of Kubernetes security and used these vulnerabilities to compromise containerized environments and escalate their privileges. Sensitive data, including customer information and intellectual property, was exfiltrated over an extended period.

The attackers operated with a clear objective of data theft and reconnaissance, leveraging custom scripts to maintain persistence and avoid detection. By February 6th, abnormal network traffic patterns triggered alerts, leading to the identification of the malicious activities.
