# Wireshark Lab: Suspicious Network Traffic Investigation

## Objective
This lab focused on capturing and analyzing network traffic in Wireshark to identify suspicious communication patterns commonly investigated by Tier 1 SOC analysts.

## Tools Used
- Wireshark
- Sample PCAP Files
- Kali Linux Network Traffic Simulation
- DNS + HTTP Protocol Analysis

## Lab Environment
- Network traffic captured from simulated workstation activity
- PCAP reviewed for abnormal behavior

## Steps Performed
1. Captured live traffic and imported PCAP samples
2. Filtered traffic by DNS, HTTP, and TCP streams
3. Identified suspicious outbound connections and beaconing behavior
4. Investigated unusual DNS queries for potential tunneling
5. Documented findings and possible threat scenarios

## Results (Screenshots)
- Wireshark packet inspection view
- Suspicious DNS query patterns
- Follow TCP stream evidence of abnormal communication

## SOC Analyst Takeaways
- Network traffic provides strong evidence during investigations
- Filtering and protocol knowledge are key SOC skills
- Beaconing behavior may indicate malware command-and-control

## Next Improvements
- Analyze real malware traffic PCAPs
- Integrate Zeek logs with Wireshark findings
