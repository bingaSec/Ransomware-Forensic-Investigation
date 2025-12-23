# Digital Forensic Ransomware Investigation

## Project Overview
This project involves a comprehensive digital forensic analysis of a ransomware attack targeting a corporate environment (Ah Yalan Dünya Corp). The investigation reconstructs the attack lifecycle from the initial phishing email to system-wide encryption and the establishment of persistence.

## Tools & Technologies
* **Autopsy:** Digital forensics platform for timeline analysis and artifact extraction.
* **FTK Imager:** Forensic imaging and data integrity verification (MD5/SHA-256).
* **Registry Viewer:** Analysis of Windows Registry for persistence mechanisms.
* **Event Log Explorer:** Analysis of Windows Event IDs (e.g., ID 7045 for service installation).

## Key Findings
* **Initial Vector:** Social engineering lure via a malicious email attachment.
* **Payload Analysis:** Identified `temp.exe` as the core ransomware engine.
* **Persistence:** Discovered a malicious service named "Windows Medical Service" created to survive system reboots.
* **Artifacts:** Documented 28 critical artifacts mapped to the Cyber Kill Chain.

## Featured Evidence
* **Forensic Timeline:** A minute-by-minute reconstruction of the breach.
* **Hash Verification:** Cryptographic proof of the malicious payloads found.
* [View Full Technical Report](./Digital_Forensics_Ransomware_Report_Bihanga.pdf)
