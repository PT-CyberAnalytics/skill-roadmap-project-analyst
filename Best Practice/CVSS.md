# CVSS 3.1 &  4.0.md

## Description
CVSS (Common Vulnerability Scoring System, https://www.first.org/cvss/v4-0/) is a vulnerability assessment system that provides a standardized way to measure their severity. CVSS 4.0 is the current version today, but version 3.1 is still actively used by many vendors. The system evaluates vulnerabilities by a number of metrics, such as impact on confidentiality, integrity, and availability, and also takes into account the complexity of exploitation, the need for privileges, user interaction, and many other metrics. Each vulnerability receives a numerical score from 0 to 10, where 10 is the maximum criticality.

## Practice
CVSS is used to classify and prioritize vulnerabilities in infrastructure. For example, after a vulnerability is discovered, an analyst can assign it a CVSS score to determine how urgently it needs to be fixed. Organizations often use CVSS scores to develop vulnerability remediation plans: the higher the score, the higher the priority for fixing. Security analysts use CVSS in reports to justify the criticality of vulnerabilities to business users and technical teams. This approach helps to clearly explain how dangerous a particular vulnerability is.

## Connection with other knowledge
CVSS is often used in conjunction with CWE, where each vulnerability has a code corresponding to its class. This allows not only to determine the nature of the vulnerability, but also its severity based on CVSS. When combined with OWASP Top 10 or the MITRE ATT&CK matrix, CVSS helps to prioritize the remediation of vulnerabilities related to specific attacks or attacker techniques. CVSS metrics can also be integrated into risk assessment systems for deeper security analytics.

## How to improve
- Review the official CVSS 3.1/4.0 documentation to understand how to use all metrics to correctly assess the risk of any vulnerability.
- Take official CVSS training: https://learn.first.org/
- Practice assessing real vulnerabilities using online calculators and analyze how different parameters affect the final score.
- Study real-world use cases of CVSS to assess multi-vector attacks and scenarios.
- Integrate CVSS 4.0 into your regular activities to demonstrate the importance of vulnerabilities to customers and colleagues based on their criticality.
- Improve your risk analysis skills by combining CVSS metrics with other sources, such as NVD (National Vulnerability Database) and pentest results, for a comprehensive threat assessment.
