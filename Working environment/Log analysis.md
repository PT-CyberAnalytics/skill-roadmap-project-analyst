# Log analysis

## Description
Log analysis is the process of examining data recorded in system logs to identify anomalous activity, traces of attacks, or events that indicate information security incidents. Logs provide detailed information about user actions, system processes, network activity, and application operation. Knowing how to analyze logs helps you understand how events unfolded, where violations may have occurred, and how to respond to identified threats.

## Practice
An analyst uses log analysis to:
- Detect attacks: Look for evidence of attacks, such as password guessing attempts, unauthorized access, or exploitation attempts.
- Account for incidents: Reconstruct the chain of events to understand how an incident occurred and what actions the attacker took.
- Detect anomalies: Identify unusual behavior, such as a spike in network traffic or attempts to execute rare commands.
- Reporting: Describe issues found, provide context, and suggestions for remediation.

## Connection with other knowledge
Log analysis is closely related to:
- Threat Intelligence: Log data can be supplemented with information about current threats (IOC, TTP of attackers).
- Threat Hunting: Logs are the main source of data for proactive threat hunting.
- Event monitoring: Logs come from monitoring systems such as SIEM or EDR and require detailed analysis.
- Information security tools: Logs help evaluate the effectiveness of security tools used, such as firewalls and antiviruses.

## How to improve
- Master working with popular log sources such as Event Viewer (Windows), Linux system logs, network logs (e.g. from Cisco or Palo Alto).
- Practice using SIEM systems (Splunk, ELK) to analyze large volumes of logs, set up correlation rules, and filter data.
- Learn log formats (e.g. JSON, CSV) and key fields to understand how the data is structured.
- Learn methods for identifying indicators of compromise (IOCs) in logs such as suspicious IP addresses, file hashes, and anomalous commands.
- Practice analyzing real logs from CTF games or open sources to develop attack detection skills.
- Learn network log analysis tools such as Wireshark or Zeek to identify traffic anomalies.
- Learn attack patterns described in MITRE ATT&CK to understand what events to look for in logs at each stage of an attack.
