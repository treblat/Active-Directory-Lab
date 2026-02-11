# Active Directory Home Lab + Attack Detection

## Objective
The purpose of this lab was to build a small enterprise-style Active Directory environment and simulate common authentication attacks in order to understand how Tier 1 SOC analysts monitor and respond to suspicious AD activity.

## Tools Used
- Windows Server 2022 (Domain Controller)
- Windows 10 Client Machine
- Kali Linux (Attacker VM)
- Sysmon + Windows Event Logs
- Splunk (Log Monitoring)

## Lab Environment
- Domain Controller: Windows Server 2022
- Client Machine: Windows 10 joined to the domain
- Attacker Machine: Kali Linux
- Monitoring: Splunk ingesting Security Event Logs

## Steps Performed
1. Installed and configured Active Directory Domain Services (AD DS)
2. Created domain users, groups, and organizational units
3. Enabled logging and installed Sysmon for enhanced visibility
4. Simulated password spraying and brute force login attempts
5. Investigated Event IDs related to failed authentication attempts (4625)
6. Documented indicators of compromise and defensive recommendations

## Results (Screenshots)
- Domain user creation and OU structure
- Splunk logs showing multiple failed login attempts
- Detection queries for abnormal authentication behavior

## SOC Analyst Takeaways
- Active Directory is a frequent target in enterprise environments
- Authentication logs provide critical evidence for Tier 1 alert triage
- Proper monitoring and account lockout policies reduce attack success

## Next Improvements
- Implement Group Policy hardening
- Add Kerberoasting detection logic
- Expand to multi-domain forest simulation
