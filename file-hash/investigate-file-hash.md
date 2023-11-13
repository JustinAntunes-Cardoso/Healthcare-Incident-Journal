# Summary: Incident Detection and Verification Lab

## Suspicious File Hash Overview

In this lab, security analysts engage in the incident detection and verification process by analyzing an artifact using VirusTotal. The focus is on capturing details related to indicators of compromise (IoCs) using the Pyramid of Pain. The scenario involves a level one security operations center (SOC) analyst at a financial services company investigating a suspicious file downloaded on an employee's computer.

## Activities

### 1. Analysis Using VirusTotal

- Utilized the Pyramid of Pain template for tracking IoCs.
- Investigated the alert and gathered details, including a SHA256 file hash.
- Accessed the VirusTotal website to analyze the file hash.
- Explored various tabs, such as Detection, Details, Relations, and Behavior, to examine IoCs.
- Reviewed security vendors' analysis, community scores, and sandbox reports to assess potential maliciousness.

### 2. IoC Identification

- Identified three distinct IoCs associated with the file hash.
  - Hash Value: Identified a secondary hash from the Details tab.
  - IP Address: Found an IP address contacted by the malware in the Relations tab.
  - Domain Name: Located a domain name associated with the malware in the Relations tab.

### 3. Pyramid of Pain Template

- Completed the Pyramid of Pain template, indicating whether the file is malicious.
- Provided reasoning based on findings from the VirusTotal report.
- Entered three identified IoCs into their respective sections in the template.

  # Results: Incident Detection and Verification Lab

## Analysis Using VirusTotal

- The file hash (SHA256: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b) has been reported as malicious by over 50 vendors.
- Further investigation revealed that the file hash corresponds to the malware named "Flagpro."
- "Flagpro" is a known threat associated with the advanced threat actor BlackTech.

## Pyramid of Pain Template

### Determination

- The file with the provided hash is confirmed to be malicious based on the high number of vendor flags and its association with the "Flagpro" malware.

### Indicators of Compromise (IoCs)

1. **Hash Values**
   - Primary Hash (SHA256): 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b
   - Secondary Hash (SHA256): 287d612e29b71c90aa54947313810a25

2. **IP Addresses**
   - Associated IP Address: 207.148.109.242

3. **Domain Names**
   - Associated Domain Name: org.miscure.com

4. **Network/Host Artifacts**
   - Artifacts: HTTP Requests

5. **Tools**
   - Identified Tool: Input Capture

6. **Tactics, Techniques, and Procedures (TTPs)**
   - Command and Control (C2)

## Conclusion

The detailed analysis using VirusTotal and the structured documentation in the Pyramid of Pain template revealed that the analyzed file hash is indeed associated with the "Flagpro" malware, commonly linked to the threat actor BlackTech. This information is critical for incident response and reinforces the importance of leveraging threat intelligence for effective cybersecurity measures.
