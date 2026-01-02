# DoS Incident Analysis Using the NIST Cybersecurity Framework

## Overview
This project documents a cybersecurity incident analysis conducted using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). The incident involved a Denial of Service (DoS) attack that disrupted internal network services by flooding the network with ICMP traffic.

## Incident Summary
The organization experienced a two-hour outage when a malicious actor exploited an unconfigured firewall to send a high volume of ICMP packets into the network. The excessive traffic overwhelmed network resources and prevented legitimate internal traffic from accessing network services.

## NIST CSF Analysis

### Identify
The affected assets included the internal network infrastructure and network-dependent services. The root cause was an unconfigured firewall that allowed unrestricted ICMP traffic into the network.

### Protect
Protective measures included implementing firewall rules for ICMP rate limiting, enabling source IP address verification, and deploying intrusion prevention systems (IPS) to reduce exposure to similar attacks.

### Detect
Detection improvements focused on deploying network monitoring tools, firewall logging, and IDS/IPS solutions to identify abnormal ICMP traffic patterns early.

### Respond
The incident response involved blocking ICMP traffic, isolating non-critical services, restoring critical systems, and documenting the incident. A formal response plan was recommended for future incidents.

### Recover
Recovery actions included restoring affected services and validating normal network operations. Future recovery plans emphasize resilience testing and continuous improvement of network security controls.

## Skills Demonstrated
- Application of the NIST Cybersecurity Framework (CSF)
- Denial of Service (DoS) attack analysis
- Network security and firewall hardening
- Incident response and recovery planning
- Security documentation and reporting
