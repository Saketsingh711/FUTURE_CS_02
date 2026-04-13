**Phishing Analysis & Awareness System 🛡️**

Cyber Security Task 2 - Future Interns
🎯 Overview

Forensic analysis of a Banco do Bradesco (Livelo) phishing campaign. This project demonstrates how manual analysis identifies "Zero-Day" threats that automated scanners miss.
🚀 Forensic Steps

    Header Analysis: Used Google Admin Toolbox to identify SPF/DMARC failures.

    Infrastructure Tracing: Identified a Root-level Postfix MTA originating from a San Francisco (SFO3) DigitalOcean VPS via VS Code.

    Payload Decoding: Deciphered Base64 content using CyberChef to extract the malicious URL: blog1seguimentmydomaine2bra.me.

    Reputation Check: Confirmed a False Negative (0/95) on VirusTotal, proving the attack's evasion capabilities.

    Visual Evidence: Rendered the fraudulent HTML using Python to confirm credential-harvesting intent.

📊 Risk Verdict

    Classification: 🔴 CRITICAL PHISHING

    Key Indicator: Geographical mismatch (US-based server for a Brazilian bank).

💡 Prevention Tips

    Verify the Return-Path for infrastructure anomalies.

    Hover over links to check for suspicious TLDs (e.g., .me).

    Always use official banking apps for "urgent" rewards.

Analyst: Saket Singh

Date: April 2026
