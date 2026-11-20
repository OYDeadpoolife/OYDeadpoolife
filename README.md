<p align="center">
  <img src="./assets/cybersecurity-banner.svg" alt="Orhay Yosef — Cybersecurity projects: networks, detection, automation and investigation." width="100%">
</p>

# Hi, I'm Orhay

**Learning cybersecurity · Working toward a SOC analyst role**

I’m learning how to spot suspicious activity, understand security logs and investigate what happened. I use these projects to practise, build useful tools and explain what I’ve learned.

[LinkedIn](https://www.linkedin.com/in/orhay-yosef) · [My projects](https://github.com/OYDeadpoolife?tab=repositories)

## What I'm working on

**Understand the network → Spot suspicious activity → Automate the checks → Investigate**

These four projects cover different parts of that process. You can explore each one on its own.

### 01 / Understanding network traffic

#### [pfSense Network Security Lab](https://github.com/OYDeadpoolife/pfsense-network-security-lab)

A plan for a small practice network, with firewall rules and sample traffic to study what gets allowed or blocked.

**Includes:** Network diagrams, made-up firewall logs, a sample packet capture and Bash / awk scripts.  
**Still to do:** Build the pfSense virtual machine and check the setup on a running firewall.

[Explore the lab](https://github.com/OYDeadpoolife/pfsense-network-security-lab#readme)

### 02 / Spotting suspicious activity

#### [SOC Detection & SIEM Lab](https://github.com/OYDeadpoolife/soc-siem-detection-lab)

A practice investigation using made-up Linux and Windows logs. It includes 12 detection rules and a walkthrough explaining what to look for.

**Includes:** Python checks, Splunk and Elastic queries, and notes on false alarms.  
**Tested so far:** The Python detection logic, as recorded in the repository. The queries still need testing in Splunk and Elastic.

[Follow the investigation](https://github.com/OYDeadpoolife/soc-siem-detection-lab/blob/main/docs/investigation-walkthrough.md)

### 03 / Making log checks easier

#### [Security Log Automation](https://github.com/OYDeadpoolife/security-log-automation)

A command-line tool that reads Linux login logs, looks for suspicious activity and writes a report. It leaves the original logs unchanged.

**Built with:** Bash and awk. Reports are available as Markdown, CSV and JSON.  
**Tested so far:** Automated checks using made-up logs. Testing with real server logs is still to do.

[Explore the tool](https://github.com/OYDeadpoolife/security-log-automation#readme)

### 04 / Taking a first look at evidence

#### [DFIR Forensics Toolkit](https://github.com/OYDeadpoolife/dfir-forensics-toolkit)

A Bash tool that gathers basic details and useful clues from a file, checks whether its contents changed during analysis, and creates a case report.

**Includes:** File details, readable text, IP addresses and links, plus SHA-256 checks before and after.  
**Tested so far:** Built-in features using made-up evidence. Connections to the real binwalk, foremost, bulk_extractor and Volatility tools still need testing.

[Explore the toolkit](https://github.com/OYDeadpoolife/dfir-forensics-toolkit#readme)

---

### About these projects

These are learning projects. The sample logs and evidence are synthetic (made up), and the investigations are fictional. Each repository explains what was tested and what still needs work.

**Find me on [LinkedIn](https://www.linkedin.com/in/orhay-yosef).**
