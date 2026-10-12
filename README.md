# Wazuh SOC Monitoring & Incident Response Lab

## Overview
A hands-on cybersecurity project using Wazuh to monitor Windows security events, investigate alerts, configure auditing, and test custom detection rules in a virtual lab.

## Tools & Technologies
- Wazuh SIEM
- Windows Security Event Logs
- Windows Event Viewer
- Linux terminal
- Oracle VirtualBox
- Wazuh custom detection rules

## Investigation Scenarios

### Scenario 1: Failed Authentication Investigation
- Investigated **Windows Event ID 4625** — failed logon attempts.
- Reviewed Wazuh alerts and rule severity.
- Investigated **Event ID 4738** — user account changes.
- Reviewed event details and verified account activity.
- Observed a Wazuh alert at rule level 5.

### Scenario 2: Repeated Failed Login Analysis
- Generated and investigated repeated incorrect Windows PIN attempts in the lab.
- Analysed repeated **Event ID 4625** events.
- Reviewed available alert details to assess a potential brute-force pattern.
- Evaluated detection coverage and documented findings.

### Scenario 3: Process Creation Monitoring
- Enabled Windows process creation auditing.
- Investigated **Event ID 4688** — a new process was created.
- Analysed process creation events in Wazuh.
- Examined built-in Wazuh rule **67027**.
- Created and tested custom Wazuh rule **100100** at rule level 5.
- Investigated `smartscreen.exe` activity and assessed it as benign.

## Technical Skills Demonstrated
- SIEM monitoring and alert investigation
- Windows Security event analysis
- Authentication failure investigation
- Process creation auditing
- Wazuh rule configuration and testing
- Basic incident triage
- Security investigation and reporting

## Project Evidence
See the report and screenshots in this repository for the lab setup, event investigations, alerts, and custom detection rule.

## Disclaimer
Conducted in a controlled virtual environment for educational and defensive security purposes.
Wazuh SOC Project — Selected Evidence Screenshots

These images were extracted from the completed Wazuh project report and retain the original screenshot content.

1. Wazuh dashboard overview
2. Scenario 1 — failed Windows login event
3. Scenario 1 — Event ID 4625 details
4. Scenario 1 — separate Event ID 4738 investigation
5. Scenario 2 — four repeated failed-login events
6. Scenario 3 — endpoint connectivity test
7. Scenario 3 — Windows process-creation auditing evidence
8. Scenario 3 — custom rule testing
9. Scenario 3 — wazuh-logtest rule match
10. Scenario 3 — live custom-rule alerts
11. Scenario 3 — Event ID 4688 details
12. Scenario 3 — expanded custom-rule alert details


