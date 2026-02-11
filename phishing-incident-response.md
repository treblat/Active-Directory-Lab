# Phishing Incident Response Simulation

## Objective
This lab simulated a phishing incident investigation and response process, focusing on how Tier 1 SOC analysts triage suspicious emails, analyze indicators, and recommend containment actions.

## Tools Used
- Email Header Analyzer
- VirusTotal (OSINT)
- Sandbox Analysis Tools
- Incident Response Documentation Template

## Lab Environment
- Simulated phishing email delivered to user inbox
- SOC analyst workflow: triage → analysis → containment

## Steps Performed
1. Collected phishing email sample and extracted headers
2. Identified suspicious sender domains and spoofing indicators
3. Investigated embedded links and attachments
4. Checked hashes and URLs against threat intelligence sources
5. Documented findings in an incident report format
6. Recommended containment actions (blocking domain, user reset)

## Results (Screenshots)
- Header analysis showing spoofing attempt
- Threat intel results for malicious URL
- Incident timeline documentation

## SOC Analyst Takeaways
- Phishing remains one of the most common initial access vectors
- Fast triage and escalation prevent further compromise
- Documentation is critical for SOC handoff and reporting

## Next Improvements
- Simulate credential harvesting campaign detection
- Add SOC ticket workflow integration
