# ITSimplera Week 3 SOC Project

## Malware Detection and Security Monitoring using pfSense, Squid Proxy, ClamAV & Wazuh SIEM

## Overview

This project was completed as part of the SOC Analyst Internship Program at ITSimplera Solutions.

The objective of this project was to build a Security Operations Center (SOC) monitoring environment capable of collecting logs, detecting malicious activity, generating security alerts, and supporting incident response.

## Technologies Used

- pfSense Firewall
- Squid Proxy
- ClamAV Antivirus
- Syslog/Syslog-NG
- Wazuh SIEM
- OpenSearch Dashboard
- Linux Ubuntu Server

## Architecture


Client
|
v
pfSense Firewall
|
v
Squid Proxy
|
v
ClamAV Malware Scanner
|
v
Syslog Collector
|
v
Wazuh SIEM
|
v
Security Alerts Dashboard


## Implementation Highlights

✔ Configured pfSense firewall logging  
✔ Integrated pfSense logs with Wazuh SIEM  
✔ Configured Squid Proxy monitoring  
✔ Integrated ClamAV malware scanning  
✔ Tested malware detection using EICAR test file  
✔ Created custom Wazuh decoder and detection rule  
✔ Verified alerts through Wazuh Dashboard  

## Custom Wazuh Detection

### Decoder

Name:

pfsense-dhcp6c


Purpose:
- Parses pfSense DHCPv6 client events.

### Rule

Rule ID:

100100


Description:

pfSense DHCPv6 Client Activity


## Project Structure


ITSimplera-Week3-SOC-Project/

├── README.md
├── Documentation.md
├── Incident_Response_Plan.md
├── screenshots/
└── wazuh/
├── decoders.xml
└── rules.xml


## Screenshots

The screenshots folder contains evidence of:
- pfSense configuration
- Squid Proxy setup
- ClamAV detection
- EICAR testing
- Wazuh alerts
- Custom detection rules

## Author

Muhammad Bilal Zeeshan

SOC Analyst Intern  
ITSimplera Solutions
