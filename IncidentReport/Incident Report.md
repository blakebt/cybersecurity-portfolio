**Incident Report Analysis**

| Summary | The organization experienced a Distributed Denial-of-Service (DDoS) attack that left the internal network compromised for two hours while steps were taken to stop the attack. Network services were stopped due to a flood of ICMP packets. No normal internal network traffic could be accessed during the attack.  |
| :---- | :---- |
| Identify | The cybersecurity team investigated the event and found that the malicious actor flooded the network with ICMP packets through an unconfigured firewall. This overwhelmed the network.  |
| Protect | The team has implemented a new firewall rule that limits the rate of incoming ICMP packets. Source IP address verification has been added to protect against spoofed IP addresses on incoming ICMP packets. Network monitoring software has been added to detect abnormal traffic. An IDS/IPS system has been added to the network to filter traffic with suspicious characteristics.  |
| Detect | The IDS/IPS system added to the network, alongside the new network monitoring software, will help in detecting suspicious traffic that may attempt to enter the network in the future. |
| Respond | During the attack, the team blocked incoming ICMP packets. All non-critical network services were taken offline and critical network services were restored.  |
| Recover | The steps taken during the attack restored critical network services. Once the attack was completely defended, all non-critical network services were restored and network activity was allowed to return to normal operation. |

