# Incident handler's journal

| Date: July 23, 2024 | Entry: #1 |
|---------------------|-----------|
| Description | Documenting a cybersecurity incident This incident occurred in the two phases: <br> 1.  Detection and Analysis: The scenario outlines how the organization first detected the ransomware incident. For the analysis step, the organization contacted several organizations for technical assistance. <br> 2.  Containment, Eradication, and Recovery: The scenario details some steps that the organization took to contain the incident. For example, the company shut down their computer systems. However, since they could not work to eradicate and recover from the incident alone, they contacted several other organizations for assistance. |
| Tool(s) used | None |
| The 5 W's | ● Who: An organized group of unethical hackers <br> ● What: A ransomware security incident <br> ● Where: At a health care company <br> ● When: Tuesday 9:00 a.m. <br> ● Why: The incident happened because unethical hackers were able to access the company's systems using a phishing attack. After gaining access, the attackers launched their ransomware on the company's systems, encrypting critical files. The attackers' motivation appears to be financial because the ransom note they left demanded a large sum of money in exchange for the decryption key. |
| Additional notes | 1. How could the health care company prevent an incident like this from occurring again? <br> 2. Should the company pay the ransom to retrieve the decryption key? |

## 1. How could the health care company prevent an incident like this from occurring again?
- Enhanced Security Awareness Training:

  - Conduct comprehensive cybersecurity awareness training for employees to recognize and avoid phishing attempts.
 - Emphasize the importance of verifying the legitimacy of email attachments and links before opening them.

- Advanced Email Filtering:

  - Implement advanced email filtering systems to detect and block phishing emails.
  - Utilize technologies that can identify and filter out malicious attachments or links.

- Regular Software Updates:

  - Ensure that all software, including operating systems and antivirus programs, is regularly updated with the latest security patches to mitigate vulnerabilities.

- Data Backup and Recovery:

  - Regularly backup critical data and maintain an effective data recovery plan to restore operations in case of a ransomware attack without succumbing to ransom demands.

- Endpoint Protection:

  - Deploy robust endpoint protection solutions to detect and prevent malware infections on individual devices.

## 2. Should the company pay the ransom to retrieve the decryption key?
The decision to pay a ransom is complex and depends on various factors. However, it's generally not advisable for several reasons:

- No Guarantee of Decryption:

  - There's no guarantee that paying the ransom will result in the decryption key being provided. Some attackers may not fulfill their promises even after payment.

-Funding Criminal Activities:

  - Paying the ransom funds criminal activities and encourages attackers to continue their malicious actions, potentially targeting the same organization again.

- Legal and Ethical Concerns:

  - Paying a ransom may violate legal and ethical standards. Some jurisdictions prohibit making payments to cybercriminals.

- Supporting Cybercrime Ecosystem:
  - Paying ransoms contributes to the profitability of the cybercrime ecosystem, enabling attackers to invest in more sophisticated attacks.

Instead of paying the ransom, the company should focus on implementing effective cybersecurity measures, having robust backup strategies, and collaborating with law enforcement and cybersecurity experts to investigate and mitigate the incident.

---

| Date: July 25, 2024 | Entry: #2 |
|---------------------|-----------|
| Description | Analyzing a packet capture file |
| Tool(s) used | Wireshark was employed to analyze a packet capture file. Wireshark, a network protocol analyzer with a graphical user interface, holds significant value in the realm of cybersecurity. Its utility lies in enabling security analysts to capture and scrutinize network traffic, thereby contributing to the identification and investigation of potential malicious activities. |
| The 5 W's | ● Who: N/A <br> ● What: N/A <br> ● Where: N/A <br> ● When: N/A <br> ● Why: N/A |

---

| Date: July 25, 2024 | Entry: #3 |
|---------------------|-----------|
| Description | Capturing my first packet |
| Tool(s) used | Tcpdump served as the tool for capturing and analyzing network traffic. Operating through the command-line interface, tcpdump, like Wireshark, functions as a network protocol analyzer. Its significance in the realm of cybersecurity lies in empowering security analysts to efficiently capture, filter, and analyze network traffic, enhancing their capabilities in detecting and responding to potential security threats. |
| The 5 W's | ● Who: N/A <br> ● What: N/A <br> ● Where: N/A <br> ● When: N/A <br> ● Why: N/A |

---

| Date: July 27, 2024 | Entry: #4 |
|---------------------|-----------|
| Description | Investigate a suspicious file hash |
| Tool(s) used | VirusTotal was utilized as an investigative tool for the analysis of files and URLs, specifically targeting potential malicious content like viruses, worms, and trojans. Functioning through a user-friendly interface, VirusTotal proves instrumental in swiftly assessing whether indicators of compromise, such as websites or files, have been flagged as malicious within the cybersecurity community. <br> <br> This incident unfolded during the Detection and Analysis phase, positioning the user as a security analyst within a Security Operations Center (SOC). Following the detection of a suspicious file hash by the implemented security systems, the task at hand involved a comprehensive analysis to validate the alert's credibility and determine the existence of an actual threat. |
| The 5 W's | ● Who: An unknown malicious actor <br> ● What: An email sent to an employee contained a malicious file attachment with the SHA-256 file hash of 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b <br> ● Where: An employee's computer at a financial services company <br> ● When: At 1:20 p.m., an alert was sent to the organization's SOC after the intrusion detection system detected the file <br> ● Why: An employee was able to download and execute a malicious file attachment via e-mail. |
| Additional notes | 1. How can this incident be prevented in the future? <br> 2. Should improving security awareness training be a priority so that employees are careful with what they click on? |

##1. How can this incident be prevented in the future?
-Enhanced Email Security:

  - Implement advanced email filtering systems to detect and block phishing emails.
  - Train employees to recognize and report suspicious emails, especially those with attachments or links.

- Incident Response Plan:

  - Develop and regularly update an incident response plan outlining the steps to be taken in the event of a security incident.
  - Conduct regular drills and simulations to ensure a swift and effective response.

## 2. Should improving security awareness training be a priority so that employees are careful with what they click on?
Yes, improving security awareness training should be a top priority for the following reasons:

- Human Firewall:

  - Employees play a crucial role in the organization's cybersecurity defense. Enhancing their awareness makes them a more effective "human firewall" against cyber threats.

-Phishing Defense:

  - Most security incidents, including the one described, involve phishing attempts. Improved awareness can empower employees to recognize and avoid falling victim to phishing.

-Risk Reduction:

  - Educated employees are less likely to engage in risky behaviors that could compromise the organization's security.

-Continuous Learning:

  - Cyber threats evolve, and ongoing training ensures that employees stay informed about the latest tactics used by cybercriminals.

-Cultural Shift:

  - A security-conscious culture fosters a collective responsibility for cybersecurity, creating a more resilient organization.

By prioritizing and investing in security awareness training, the organization can significantly reduce the likelihood of similar incidents in the future.
