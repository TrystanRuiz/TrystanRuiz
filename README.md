# Trystan Ruiz

[Portfolio](https://trystanruiz.tech) | [LinkedIn](https://linkedin.com/in/trystanruiz)

UCF IT student focused on cybersecurity, SIEM, SOC operations, and homelab infrastructure. Building hands-on projects in Splunk, Sysmon, Cowrie, Linux hardening, and incident analysis. CompTIA Security+ certified, Network+ and CySA+ in progress.

Seeking cybersecurity / SOC analyst / security operations internships where I can contribute in monitoring, detection, triage, and hands-on lab work.

## Honeypot & SIEM

- **[T-POT Honeypot Threat Intelligence](https://github.com/TrystanRuiz/tpot-honeypot-threat-intel)** - Deployed T-POT Standard on Proxmox with 21 sensors capturing 762k+ events from 115 unique IPs. Built a Python pipeline that pulls attacker IPs from Elasticsearch, scores them against AbuseIPDB, and auto-pushes blocks to OPNsense via REST API. Rewrote it in async Python and cut the check time by 76%, then validated end-to-end blocking using known malicious IPs spoofed from Kali.

- **[Cowrie SSH Honeypot + SIEM](https://github.com/TrystanRuiz/cowrie-honeypot-siem)** - Set up a Cowrie SSH honeypot on Proxmox and forwarded logs to Splunk for centralized analysis. Simulated a brute-force attack from Kali using Hydra, built custom dashboards to profile attacker behavior per IP, and hardened the host with UFW and a custom Fail2ban jail.

- **[Splunk SIEM Environment](https://github.com/TrystanRuiz/Splunk-Sysmon-SIEM)** - Self-hosted Splunk Enterprise ingesting Windows Security events and Sysmon telemetry. Built SOC dashboards tracking LOLBin abuse, encoded PowerShell, lsass access attempts, and brute force patterns, all mapped to MITRE ATT&CK technique IDs.

## SOC & Incident Response

- **[SOC Writeups](https://github.com/TrystanRuiz/SOC-Writeups)** - Alert triage, phishing analysis, and incident report writeups from TryHackMe and LetsDefend simulated SOC environments.

## Infrastructure

- **[HomeLab](https://github.com/TrystanRuiz/HomeLab)** - Proxmox VE running 7 LXC containers and 2 VMs including Splunk, Grafana/Prometheus, Gitea, Authelia SSO, and Nginx Proxy Manager. Kali and Windows VMs for attack simulation, with Tailscale subnet routing for remote access.

## Technical Skills

Splunk, Sysmon, Cowrie, T-POT, Suricata, ELK Stack, Python, asyncio, aiohttp, AbuseIPDB, OPNsense, Hydra, UFW, Fail2ban, Proxmox, Linux, Windows Server, Grafana, Prometheus, Tailscale, MITRE ATT&CK, log analysis, alert triage, incident reporting, blue team operations
