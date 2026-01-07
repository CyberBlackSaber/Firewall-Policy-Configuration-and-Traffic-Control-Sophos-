# Firewall Policy Configuration and Traffic Control (Sophos)

## Overview
This project demonstrates configuring firewall policies using Sophos Firewall to control network traffic and enforce secure communication practices.

## Objective
To reduce security risk by blocking insecure protocols and allowing encrypted services based on least-privilege principles.

## Tools Used
- Sophos Firewall (Simulation)
- Test client and server systems

## Firewall Rules Implemented

### 1. Block HTTP Traffic
- Implemented a firewall rule to block HTTP (unencrypted) traffic.
- Prevents transmission of data over insecure plaintext protocols.
- Encourages use of secure alternatives such as HTTPS.

### 2. Allow FTP over TLS
- Configured a rule to allow FTP traffic secured with TLS encryption.
- Ensures file transfer communication is encrypted.
- Demonstrates secure service enablement while maintaining protection.

## What I Did
- Defined firewall policies based on protocol security risks
- Applied allow/deny rules aligned with security best practices
- Tested traffic behavior to confirm rules were enforced correctly

## Security Relevance
- Demonstrates firewall policy management and protocol filtering
- Shows understanding of secure vs insecure communication
- Relevant to Security Analyst and SOC roles involving network defense

