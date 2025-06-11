<h1> Use the NIST Cybersecurity Framework to respond to a security incident</h1>

<h2>Scenario</h2>

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

-A new firewall rule to limit the rate of incoming ICMP packets

-Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

-Network monitoring software to detect abnormal traffic patterns

-An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

<h2>Project Description</h2>

This project aims to enhance the cybersecurity posture of the organization by addressing vulnerabilities and improving resilience against cyber threats, particularly Distributed Denial of Service (DDoS) attacks. Using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), the project will focus on identifying security risks, implementing protective measures, enhancing detection capabilities, responding effectively to incidents, and ensuring efficient recovery processes. The goal is to establish a comprehensive and proactive security strategy that safeguards the organization's critical assets and ensures business continuity.

<h2>Task</h2>

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. 

-Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

-Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

-Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

-Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

-Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

<h2>Incident report analysis</h2>

</head><body class="c12 doc-content"><div><p class="c7 c18"><span class="c14"></span></p></div><p class="c7 c10"><span class="c4"></span></p><p class="c13 c19"><span class="c6"></span></p><p class="c7 c8"><span class="c9 c16"></span></p><table class="c15"><tr class="c1"><td class="c0" colspan="1" rowspan="1"><p class="c5"><span class="c17">Summary</span></p></td><td class="c2" colspan="3" rowspan="1"><p class="c5"><span class="c3">The company experienced a security event when all network services suddenly stopped responding. The cybersecurity team found the disruption was caused by a distributed denial of services (DDoS) attack through a flood of incoming ICMP packets. The team responded by blocking the attack and stopping all non-critical network services, so that critical network services could be restored.</span></p></td></tr><tr class="c1"><td class="c0" colspan="1" rowspan="1"><p class="c5"><span class="c3">Identify</span></p></td><td class="c2" colspan="3" rowspan="1"><p class="c5"><span class="c3">A malicious actor or actors targeted the company with an ICMP flood attack. The entire internal network was affected. All critical network resources needed to be secured and restored to a functioning state.</span></p></td></tr><tr class="c1"><td class="c0" colspan="1" rowspan="1"><p class="c5"><span class="c3">Protect</span></p></td><td class="c2" colspan="3" rowspan="1"><p class="c5"><span class="c9">The </span><span class="c3">cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.</span></p></td></tr><tr class="c20"><td class="c0" colspan="1" rowspan="1"><p class="c5"><span class="c3">Detect</span></p></td><td class="c2" colspan="3" rowspan="1"><p class="c5"><span class="c3">The cybersecurity team configured source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets and implemented network monitoring software to detect abnormal traffic patterns. </span></p></td></tr><tr class="c1"><td class="c0" colspan="1" rowspan="1"><p class="c5"><span class="c3">Respond</span></p></td><td class="c2" colspan="3" rowspan="1"><p class="c5"><span class="c9">For future security events, the cybersecurity team will isolate affected systems to prevent further disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. Then, the team will analyze network logs to check for suspicious and abnormal activity</span><span class="c9">.</span><span class="c3">&nbsp;The team will also report all incidents to upper management and appropriate legal authorities, if applicable.</span></p></td></tr><tr class="c1"><td class="c0" colspan="1" rowspan="1"><p class="c5"><span class="c3">Recover</span></p></td><td class="c2" colspan="3" rowspan="1"><p class="c5"><span class="c9">To recover from a</span><span class="c9">&nbsp;DDoS </span><span class="c3">attack by ICMP flooding, access to network services need to be restored to a normal functioning state. In the future, external ICMP flood attacks can be blocked at the firewall. Then, all non-critical network services should be stopped to reduce internal network traffic. Next, critical network services should be restored first. Finally, once the flood of ICMP packets have timed out, all non-critical network systems and services can be brought back online.</span></p></td></tr></table><p class="c8 c7"><span class="c3"></span></p><p class="c5 c7 c13"><span class="c3"></span></p></body></html>

The Above table summarises a complete incident report analysis established based on the NIST Cybersecurity Framework :

1-What type of attack occurred, the scope of the incident, and its impact to the organization.

2-Potential network vulnerabilities and protection measures.

3-Detection tools to monitor and secure the network.

4-How to respond to cybersecurity incidents in the future.

5-Recovery plans to restore normal operations.




