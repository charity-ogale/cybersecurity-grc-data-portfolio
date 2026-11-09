# Metasploit Practical Penetration Testing

## Project Overview
This project documents a practical penetration-testing exercise conducted in a controlled lab environment using Kali Linux and the Metasploit Framework.

The exercise involved reconnaissance, exploit research, module configuration, exploitation and post-exploitation activities against an intentionally vulnerable EyesOfNetwork target.

## Objectives
- Perform network and service discovery.
- Research known vulnerabilities and available exploits.
- Configure and execute a Metasploit exploit module.
- Establish and interact with a Meterpreter session.
- Understand the stages of a penetration-testing workflow.

## Tools and Technologies
- Kali Linux
- Metasploit Framework
- Nmap
- ARP-scan
- fping
- SearchSploit
- Meterpreter

## Practical Activities

### 1. Network Reconnaissance
Performed network discovery using ARP-scan and fping, followed by Nmap scanning to identify available hosts, open ports and running services.

### 2. Exploit Research
Used SearchSploit and Metasploit to investigate exploit information relating to the EyesOfNetwork application.

### 3. Metasploit Configuration
Selected and reviewed the following module:

`exploit/linux/http/eyesofnetwork_autodiscovery_rce`

Configured the target and payload options for the controlled lab exercise.

### 4. Exploitation
Executed the selected exploit against the intentionally vulnerable target.

The exercise successfully established a Meterpreter session.

### 5. Post-Exploitation
Performed basic post-exploitation activities, including directory navigation and examination of files on the target system.

## Key Findings
- Identified network hosts and exposed services.
- Researched an application-specific remote code execution exploit.
- Successfully established a Meterpreter session.
- Demonstrated basic post-exploitation interaction.

## Security Considerations
The exercise demonstrates why vulnerable application components and exposed services should be identified, assessed and remediated.

Recommended security measures include:
- Keep applications and operating systems updated.
- Apply relevant security patches.
- Restrict unnecessary network access.
- Monitor systems for suspicious activity.
- Conduct regular vulnerability assessments.

## Evidence
Practical screenshots and supporting documentation will be provided in the screenshots folder.

## Skills Demonstrated
- Network reconnaissance
- Port and service scanning
- Vulnerability research
- Metasploit Framework
- Exploitation fundamentals
- Meterpreter
- Post-exploitation fundamentals
- Security documentation

## Scope and Disclaimer
This exercise was conducted against an intentionally vulnerable target in a controlled lab environment for educational purposes. No unauthorised systems were targeted.
[View Metasploit Penetration Testing Evidence](screenshots/Metasploit-Penetration-Testing-Evidence.pdf)
