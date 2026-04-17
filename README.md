# Trystan Ruiz

UCF IT student focused on cybersecurity, SIEM, SOC operations, and homelab infrastructure. Building hands-on projects in Splunk, Sysmon, Cowrie, Linux hardening, and incident analysis. CompTIA Security+ certified, Network+ and CySA+ in progress.

Seeking cybersecurity / SOC analyst / security operations internships where I can contribute in monitoring, detection, triage, and hands-on lab work.

## Honeypot & SIEM

- **[T-POT Honeypot Threat Intelligence](https://github.com/TrystanRuiz/tpot-honeypot-threat-intel)** `In Progress` - Deployed T-POT Standard Edition on Proxmox with 21 honeypot sensors across 50+ ports, capturing 762,000+ attack events from 115 unique IPs. Built a Python pipeline that extracts attacker IPs from Elasticsearch, scores them against AbuseIPDB, and pushes high-risk IPs to an OPNsense firewall blocklist via REST API automatically. Rewrote the pipeline in async Python using asyncio and aiohttp, cutting check time by 76% (34s to 8s on 90 IPs). Validated end-to-end blocking using known malicious IPs spoofed from Kali hitting the honeypot sensors.
- **[Cowrie SSH Honeypot + SIEM](https://github.com/TrystanRuiz/cowrie-honeypot-siem)** - Built a Cowrie SSH honeypot integrated with Splunk to capture and analyze brute-force activity; simulated attacks with Hydra and hardened the host using UFW and Fail2ban. Custom Splunk dashboards profile attacker behavior per IP, and fail2ban auto-bans after 3 failed attempts.
- **[Splunk SIEM Environment](https://github.com/TrystanRuiz/Splunk-Sysmon-SIEM)** - Self-hosted Splunk Enterprise ingesting Windows Security + Sysmon telemetry, with custom SOC dashboards tracking LOLBin abuse, encoded PowerShell, lsass access, and brute force patterns, all mapped to MITRE ATT&CK technique IDs.

## SOC & Incident Response

- **[SOC Writeups](https://github.com/TrystanRuiz/SOC-Writeups)** - Alert triage, phishing analysis, and incident report writeups from TryHackMe and LetsDefend simulated SOC environments.

## Infrastructure

- **[HomeLab](https://github.com/TrystanRuiz/HomeLab)** - Proxmox VE hypervisor running 7 LXC containers and 2 VMs: Splunk SIEM, Grafana/Prometheus monitoring, Gitea, Authelia SSO, Nginx Proxy Manager, and Kali/Windows attack simulation environments. Tailscale subnet router for remote access.

## Technical Skills

Splunk, Sysmon, Cowrie, T-POT, Suricata, ELK Stack, Python, asyncio, aiohttp, AbuseIPDB, OPNsense, Hydra, UFW, Fail2ban, Proxmox, Linux, Windows Server, Grafana, Prometheus, Tailscale, MITRE ATT&CK, log analysis, alert triage, incident reporting, blue team operations

## Connect

[Portfolio](https://trystanruiz.tech) | [LinkedIn](https://linkedin.com/in/trystanruiz)
