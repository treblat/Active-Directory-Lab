# Active Directory Home Lab + Hardening

## Objective
The purpose of this lab was to build a small enterprise-style Active Directory environment, configure windows server, setup users/OU's, create, modify, assign GPO's, and harden AD DS.

## Tools Used
- VMWare for Workstation Pro
- Windows Server 2022 (Domain Controller)
- Windows Server 2022 (Replicated Domain Controller)
- Windows 10 Client Machine

## Lab Environment
- Domain Controller: Windows Server 2022
- Domain Controller: Windows Server 2022 (Replicated Domain Controller)
- Client Machine: Windows 10 joined to the domain
 
## Steps Performed
1. Created internal network
2. Installed and configured Active Directory Domain Services (AD DS) and DNS and configured static IP addressing for all nodes.
3. Created domain users, groups, and organizational units and assigned users.
4. Deployed GPO's to groups and individual users such as password, and lockout policies.
5. Added a second Domain Controller using replication for high availability, redundancy and fault tolerance.
6. Performed AD Hardening
 
## [Results (Screenshots)](https://github.com/treblat/Active-Directory-Lab/blob/main/AD%20DS%20Homelab%20screenshots.pdf)
- Domain creation
- Group Policy Management Console
- AD DS Hardening

## Takeaways
- Correct network configuration is crucial for ensuring connection to a domain.
- Replication of a DC provides high availability, redundancy and fault tolerance.
- AD simplifies and centralizes multiple aspects of managing a domain in an enterprise envrionment.
- Hardening AD DS reduces the attack surface from many different types of attacks.
- Active Directory is a frequent target in enterprise environments.

## Next Improvements
- Harden AD DS further
- Implement Splunk SIEM Detection Lab
- Vulnerability Management (Nessus)
- Phishing Incident Response
- Wireshark Traffic Analysis
