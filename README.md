<h1>Incident Report Analysis – DDoS Attack (ICMP Flood)</h1>

<h2>Description</h2>
<p>
This project demonstrates my ability to analyze and respond to a Distributed Denial-of-Service (DDoS) attack using structured incident response methodologies. The scenario focuses on identifying vulnerabilities, implementing mitigation strategies, and aligning actions with the NIST Cybersecurity Framework (CSF).
</p>

<h2>Key Skills Demonstrated</h2>
<ul>
  <li>Incident Response & Analysis</li>
  <li>DDoS Attack Identification (ICMP Flood)</li>
  <li>Firewall Configuration & Hardening</li>
  <li>Network Traffic Analysis</li>
  <li>NIST CSF Application (Identify, Protect, Detect, Respond, Recover)</li>
</ul>

<h2>Tools & Technologies</h2>
<ul>
  <li>Firewall Configuration</li>
  <li>Network Monitoring Tools</li>
  <li>IDS/IPS Systems</li>
</ul>

<h2>Scenario Overview</h2>
<p>
A multimedia company experienced a DDoS attack that disrupted internal network services for approximately two hours. The attack consisted of a high volume of ICMP packets that overwhelmed network resources, preventing legitimate access to systems.
</p>

<h2>Root Cause</h2>
<ul>
  <li>Misconfigured firewall allowed unrestricted ICMP traffic</li>
  <li>No rate limiting or source validation in place</li>
  <li>Lack of proactive monitoring for abnormal traffic spikes</li>
</ul>

<h2>Response Actions Taken</h2>
<ul>
  <li>Blocked incoming ICMP traffic to stop the attack</li>
  <li>Disabled non-critical services to preserve system resources</li>
  <li>Prioritized restoration of critical business systems</li>
  <li>Performed log analysis to investigate attack origin</li>
</ul>

<h2>Mitigation & Security Improvements</h2>
<ul>
  <li>Implemented ICMP rate limiting on firewall</li>
  <li>Enabled source IP validation to prevent spoofing</li>
  <li>Deployed network monitoring for anomaly detection</li>
  <li>Integrated IDS/IPS for real-time threat detection</li>
</ul>

<h2>NIST Cybersecurity Framework Application</h2>
<ul>
  <li><b>Identify:</b> Discovered firewall misconfiguration and network exposure</li>
  <li><b>Protect:</b> Strengthened firewall rules and security policies</li>
  <li><b>Detect:</b> Implemented monitoring and alerting for abnormal traffic</li>
  <li><b>Respond:</b> Contained attack and restored critical services</li>
  <li><b>Recover:</b> Restored operations and updated incident response plan</li>
</ul>

<h2>Outcome</h2>
<ul>
  <li>Network services restored within 2 hours</li>
  <li>No data loss reported</li>
  <li>Improved network security posture and monitoring capabilities</li>
</ul>

<h2>Key Takeaway</h2>
<p>
This project highlights the importance of proper firewall configuration, proactive monitoring, and structured incident response. It demonstrates my ability to analyze security incidents and implement effective mitigation strategies in a real-world scenario.
</p>

<h2>Source</h2>
<p>
Scenario adapted from coursework in the Google Cybersecurity Professional Certificate program.
</p>
