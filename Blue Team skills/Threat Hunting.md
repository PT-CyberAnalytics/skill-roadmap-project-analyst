# Threat Hunting

## Description
Threat Hunting is a proactive process of searching for threats in the IT infrastructure that have not been detected by classic security tools, such as antiviruses or SIEM. The main goal is to identify hidden attacks or abnormal activity that may indicate the presence of intruders in the system. This process requires deep data analysis, understanding the principles of operation of various systems and the use of indicators of compromise (IOC), as well as knowledge of attack tactics and techniques from MITRE ATT&CK.

## Practice
An analyst can use Threat Hunting to:
- Find anomalies: Analyze logs, network traffic, and endpoint data to identify suspicious activity such as unusual network connections, changes in process behavior, unusual task creation, file modification, unexpected data in the system, and illegitimate events.
- Work with IOCs: Use indicators of compromise (file hashes, IP addresses, domains) to find traces of attackers.
- Develop hypotheses: Build hypotheses about potential threats based on current system data and knowledge of attack methods.
- Respond to detected threats: Prepare recommendations for eliminating threats, monitoring, and improving protection to prevent attacks from recurring.

## Connection with other knowledge
Threat Hunting is closely related to other aspects of Blue Team expertise:
- Threat Intelligence: Intelligence helps to build hypotheses for searching for threats and to refine the analysis criteria.
- Information security tools: EDR and SIEM systems are the main tools/sources for conducting Threat Hunting.
- Event monitoring: Data from event logs is used to search for abnormal activity.
- Attack models: Knowledge of MITRE ATT&CK and Cyber ​​Kill Chain helps to understand at what stages of the attack it is possible to detect traces of intruders, as well as points of penetration into the infrastructure and vectors of cyberattack development.

## How to improve
- Follow Threat Hunting reports and case studies to learn examples of successful attack detection.
- Learn how EDR and SIEM systems work to hunt for threats.
- Study attack models such as MITRE ATT&CK to understand attacker tactics and techniques and find their traces.
- Practice analyzing logs and network traffic data to identify anomalies. For example, work with data from Wireshark.
- Learn methods for analyzing indicators of compromise (IOC) and using Yara rules to find malicious activity.
- Improve your skills in building hypotheses and testing them based on data about current system activity and information about new attack methods.
- Participate in exercises and attack simulations (e.g. CTF games) to sharpen your threat hunting skills in real-world conditions.
- Master the automation of the Threat Hunting process using Python or other data analysis tools.
