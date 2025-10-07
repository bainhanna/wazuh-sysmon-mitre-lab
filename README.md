# wazuh-sysmon-mitre-lab
Mini SOC Lab using Wazuh, Sysmon, and MITRE ATT&amp;CK to simulate and detect Windows-based attacks.

This project simulates a small Security Operations Center (SOC) using:

- Wazuh SIEM
- Windows 10 VM with Sysmon
- MITRE ATT&CK techniques (T1059, T1105, etc.)
- Atomic Red Team for simulation

Files

- `sysmon-config.xml` – Sysmon logging rules
- `incident-report.pdf` – Summary of attack detection
- `screenshots/` – Wazuh dashboard outputs

Goal

Detect, analyze, and respond to simulated Windows attacks in a controlled lab.
