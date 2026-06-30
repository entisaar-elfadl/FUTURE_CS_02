# FUTURE_CS_02

## Phishing Email Analysis

This repository contains my submission for **Task 2** of the **Future Interns Cyber Security Internship**.

The objective of this task was to analyse real phishing email samples obtained from a public research dataset, identify phishing indicators, investigate embedded URLs, and document the findings in a professional security report.

## Project Objectives

The investigation focused on:

- Analysing raw `.eml` email files
- Extracting and interpreting email headers
- Identifying phishing indicators
- Examining social engineering techniques
- Defanging malicious URLs
- Investigating URLs using VirusTotal and urlscan.io
- Producing a cybersecurity analysis report with recommendations

## Tools Used

- Linux (Ubuntu/WSL)
- Visual Studio Code
- Bash Commands (`cat`, `grep`)
- VirusTotal
- urlscan.io
- Microsoft Word
- SpamAssassin

## Repository Structure

```text
FUTURE_CS_02
│
├── sample email evidence
│   ├── extra analysis evidence
│   │   ├── sample1.png
│   │   ├── sample2.png
│   │   ├── sample3.png
│   │   ├── sample1_virustotal.png
│   │   ├── sample2_virustotal.png
│   │   ├── sample3_virustotal.png
│   │   ├── defanging_screenshot_sample1.png
│   │   ├── defanging_screenshot_sample2.png
│   │   └── defanging_screenshot_sample3.png
│   │
│   ├── phishing2.mbox
│   ├── sample1.eml
│   ├── sample2.eml
│   └── sample3.eml
│
├── Task 2 Report.pdf
└── README.md
```

## Investigation Methodology

For each phishing email sample, I completed the following steps:

1. Opened the raw `.eml` file.
2. Extracted key email headers using Linux commands.
3. Examined the sender, recipient, subject line and spam headers.
4. Analysed the email body for phishing indicators.
5. Identified and defanged embedded URLs.
6. Investigated each URL using VirusTotal and urlscan.io.
7. Documented the findings and classified each email.

## Skills Demonstrated

- Email Header Analysis
- Phishing Detection
- Social Engineering Analysis
- Linux Command Line
- URL Defanging
- Threat Intelligence
- Technical Documentation
- Cybersecurity Reporting

## Key Findings

Three phishing email samples were analysed, each impersonating a different trusted organisation:

- Credit Union
- PayPal
- eBay

Although each campaign used different social engineering techniques, they all attempted to persuade recipients to interact with malicious links by creating urgency and exploiting trust.

A notable finding was that none of the embedded URLs were detected as malicious by VirusTotal during the investigation. This reinforces the importance of combining automated security tools with manual analysis when investigating phishing emails.

**Author**

**Entisaar Elfadl**

Bachelor of Business Science (Computer Science)

University of Cape Town

Future Interns Cyber Security Internship