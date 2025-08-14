<h1> Sample Incident Report</h1>

 

<h2>Description</h2>
Incident reports are important for documenting security events, helping to identify patterns, and preventing future incidents. I use them to ensure accountability and support effective mitigation strategies.
<br />





<h2>Cybersecurity Scenario:</h2>

<p align="center">
DDoS Attack Response and Mitigation
  I am a cybersecurity analyst working for a multimedia company that provides a range of digital services, including web design, graphic design, and social media marketing solutions for small businesses. Recently, our organization experienced a significant cybersecurity incident in the form of a distributed denial-of-service (DDoS) attack that temporarily compromised our internal network. The attack lasted approximately two hours and caused major disruptions to our normal business operations.

During the attack, our network services suddenly became unresponsive. Internal users were unable to access critical systems, applications, or resources because the attack involved a massive flood of ICMP packets targeting our network. Essentially, the attack overwhelmed our systems with a high volume of traffic, preventing legitimate users from performing their work. This type of attack is particularly dangerous because it can paralyze a network in a very short amount of time if proper controls are not in place.

The incident management team quickly identified the source of the problem and responded immediately. Their first action was to block all incoming ICMP traffic to prevent further flooding. Next, they took non-critical network services offline to preserve system stability and prioritize the restoration of essential services. Critical business functions were restored to operational status as quickly as possible while the network continued to be monitored for additional anomalies.

Once the immediate threat was mitigated, our cybersecurity team conducted a thorough investigation to determine how the attack was carried out. We discovered that the malicious actor exploited a misconfigured firewall, which allowed an uncontrolled stream of ICMP ping requests to enter the network. This vulnerability provided the attacker with the ability to flood our network and disrupt operations effectively.
 Mitigation Measures Implemented
 Firewall Rate Limiting: Configured a new firewall rule to limit the rate of incoming ICMP packets.  
Source IP Verification: Enabled source IP address validation on the firewall to detect and block spoofed IP addresses.  
Network Monitoring: Deployed advanced monitoring software to track traffic patterns and detect abnormal spikes.  
IDS/IPS Integration: Set up an intrusion detection and prevention system to filter suspicious traffic.

 NIST Cybersecurity Framework (CSF) Steps Applied
1. Identify: Conduct regular audits of networks, systems, devices, and access privileges to identify potential vulnerabilities.  
2. Protect: Implement policies, procedures, training, and technical controls to safeguard critical assets.  
 3. Detect: Improve monitoring to quickly identify unusual traffic patterns or suspicious activity.  
4. Respond: Refine incident response protocols to contain, neutralize, and analyze attacks effectively.  
 5. Recover: Restore affected systems and data while updating security strategies to prevent recurrence.

 Overall, this DDoS incident highlighted both strengths and weaknesses in our network infrastructure. By analyzing the attack, implementing technical controls, and following the structured NIST CSF, we strengthened our defenses, improved incident response, and reduced the likelihood of future attacks. Continuous monitoring, proactive risk assessment, and team collaboration are essential in maintaining a secure and resilient network environment.

<br />
<br />
Summary:  <br/>
 Recently, the organization I am working to secure experienced a Distributed Denial-of-Service (DDoS) attack. During the incident, network services were disrupted due to a flood of ICMP packets. In response, the incident management team blocked all incoming ICMP traffic and disabled non-essential network services to contain the impact. A subsequent investigation by the cybersecurity team revealed that the attack was made possible through an improperly configured firewall.
 Mitigation and Response Steps
> - Blocked all incoming ICMP traffic to prevent further disruption.  
> - Disabled non-essential network services to prioritize critical operations.  
> - Conducted a full investigation to identify the source and method of the attack.  
> - Corrected firewall misconfigurations to prevent similar attacks in the future.  
> - Implemented monitoring and alerting to detect abnormal traffic patterns.  

<br />
<br />
Identify: <br/>
 A review of the incident revealed that a firewall was not properly configured. This misconfiguration increased the attack surface by allowing ICMP traffic from external sources into the internal network. As a result, attackers were able to overwhelm the network with ICMP requests, causing a denial-of-service (DoS). The investigation also showed that the organization did not have the appropriate firewall rules in place to block this type of traffic.
>
>  Key Findings
> - Firewall was improperly configured, allowing external ICMP traffic.  
> - The network was vulnerable to DoS attacks due to this misconfiguration.  
> - Appropriate firewall rules were not in place to block malicious traffic.  
> - Corrective actions are required to secure the network against similar attacks.

<br />
<br />
Protect:  <br/>
 Network Protection Measures
> To protect the network from similar threats, the security team implemented the following changes:

> - A new firewall rule to limit the rate of incoming ICMP packets.  
> - Enabled source IP verification on the firewall to block spoofed traffic.  
> - Updated the organization's firewall configuration review policy.  
> - Scheduled regular firewall audits and vulnerability scans.

<br />
<br />
Detect:  <br/>
Threat Detection Enhancements
 To improve threat detection and reduce response time, the following changes were implemented:

 - Deployed network monitoring software to detect abnormal traffic patterns.  

 - Installed an Intrusion Detection/Prevention System (IDS/IPS) to analyze and filter incoming ICMP packets.  

- Configured alerts to notify security personnel of large spikes in ICMP traffic or suspected DDoS activity.

<br />
<br />
Respond:  <br/>
Incident Response Actions
During the incident, the following actions were taken:
 
- Blocked all incoming ICMP traffic.  

 - Disabled non-critical services to preserve bandwidth and resources.  

 - Prioritized restoring critical business services.  
 
 - Conducted a forensic review of the firewall and network logs to trace the origin and method of the attack.

<br />
<br />
Recover:  <br/>
 Recovery and Post-Incident Actions

 The IT team restored normal network operations within two hours. No data loss was reported. Following the recovery, the company:

- Performed a post-incident review to identify lessons learned.
 
- Updated its incident response plan to include DDoS-specific procedures.  

- Communicated the incident and remediation steps to stakeholders and executive leadership.

Reflections:  <br/>

A misconfigured firewall can leave the network vulnerable and lead to serious damage.

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
