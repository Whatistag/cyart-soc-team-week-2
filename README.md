# SOC-OPERATIONS-REPORT

PART 1 – THEORETICAL KNOWLEDGE
________________________________________
1️⃣ Alert Priority Levels

🔹 Severity Levels

Critical

  Represents an immediate and severe threat to the organization. Usually involves active exploitation, ransomware, or data breaches requiring urgent response.

High

  Indicates serious security incidents such as unauthorized admin access or confirmed malware infection. Needs fast investigation but may not yet be causing major damage.

Medium

  Suspicious or potentially harmful activity like repeated login failures or brute-force attempts. Requires monitoring and analysis.

Low

  Minor or informational alerts such as port scans or policy violations. These usually have minimal business impact.
________________________________________
🔹 Assignment Criteria

Asset Criticality
  Priority depends on the importance of the affected system. A production server or domain controller is more critical than a test VM or user laptop.

Exploit Likelihood
  If a public exploit exists or the vulnerability is actively exploited, the priority increases significantly.

Business Impact
  Incidents that may cause financial loss, data exposure, or regulatory penalties are given higher priority.

🔹 CVSS Scoring
  CVSS (Common Vulnerability Scoring System) is a standardized method to measure vulnerability severity.

Example:

  Log4Shell had a CVSS score of 9.8, meaning it was critical because it allowed remote code execution and had a public exploit.

Severity Mapping:

•	9.0–10.0 → Critical

•	7.0–8.9 → High

•	4.0–6.9 → Medium

•	0.1–3.9 → Low

Reference frameworks:

•	FIRST (CVSS Guide)

•	NIST SP 800-61
________________________________________

2️⃣ Incident Classification

🔹 Incident Categories

Malware

  Malicious software infections like trojans, worms, ransomware, or spyware.

Phishing

  Fraudulent emails or messages designed to steal credentials or deliver malware.

DDoS (Distributed Denial of Service)

  Attack that overwhelms a system or network with traffic, causing service disruption.

Insider Threat

  Security risk originating from employees or authorized users misusing access.

Data Exfiltration

  Unauthorized transfer of sensitive data outside the organization.

🔹 MITRE ATT&CK Mapping

Framework developed by
MITRE Corporation
  MITRE ATT&CK provides a structured matrix of attacker tactics and techniques.

Examples:

•	Phishing → T1566

•	Exploit Public-Facing Application → T1190

This helps SOC analysts standardize detection and reporting.
________________________________________
3️⃣ Basic Incident Response Lifecycle

Based on NIST SP 800-61

Preparation
    Establish policies, tools, training, and response plans before incidents occur.

Identification
    Detect and confirm security incidents using alerts, logs, and analysis.

Containment
    Limit the damage by isolating affected systems and blocking malicious activity.

Eradication
    Remove malware, close vulnerabilities, and eliminate root cause.

Recovery

  Restore systems to normal operation and monitor for reinfection.

Lessons Learned

  Conduct post-incident review to improve future response and strengthen security controls.

