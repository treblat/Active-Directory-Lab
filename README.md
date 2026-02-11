# Splunk SIEM Detection: Brute Force Login Alerts

## Objective
This lab simulated a brute force login attack and created a Splunk detection rule to alert on excessive failed authentication attempts, mirroring real Tier 1 SOC monitoring workflows.

## Tools Used
- Splunk Enterprise
- Windows Security Logs
- Sysmon
- Kali Linux (Attack Simulation)

## Lab Environment
- Target Machine: Windows Server / Domain Account
- Attacker Machine: Kali Linux
- SIEM: Splunk ingesting Event ID logs

## Steps Performed
1. Forwarded Windows Security logs into Splunk
2. Generated repeated failed login attempts against a domain account
3. Queried Event ID 4625 (failed logons)
4. Built correlation logic to detect high-frequency failures
5. Created an alert trigger and dashboard panel

## Results (Screenshots)
- Splunk search results for failed authentication spikes
- Alert rule configuration page
- Dashboard visualization of attack activity

## SOC Analyst Takeaways
- Brute force attacks create recognizable authentication patterns
- Splunk alerting reduces time-to-detection
- Tier 1 analysts rely heavily on event correlation and context

## Next Improvements
- Add geo-IP anomaly detection
- Expand rule to detect successful compromise after failures
