**Subject**: Vulnerability Remediation Scripts for Testing and Deployment

Hi Infrastructure Team,

Following our initial vulnerability scan and assessment, we’ve created a set of remediation scripts to assist with addressing the most critical issues. These scripts are designed to be easily integrated into your existing deployment workflows (e.g., SCCM) and should streamline your initial remediation efforts.

### Vulnerabilities and Remediations:
1. [**Third-Party Software Removal (Wireshark)**](https://github.com/cherinejoseph/cyber-range-res/blob/main/automation/remediation-wireshark-uninstall.ps1)
2. [**Windows OS Secure Configuration (Insecure Protocols)**](https://github.com/cherinejoseph/cyber-range-res/blob/main/automation/toggle-protocols.ps1)
3. [**Windows OS Secure Configuration (Insecure Ciphersuites)**](https://github.com/cherinejoseph/cyber-range-res/blob/main/automation/toggle-cipher-suites.ps1)
4. [**Windows OS Secure Configuration (Guest Account Group Membership)**](https://github.com/cherinejoseph/cyber-range-res/blob/main/automation/toggle-guest-local-administrators)

Please test these scripts in your development or staging environment before deploying them into production.

If you have any questions or would like to request modifications, feel free to reach out. I look forward to our next meeting and discussing the progress further.

Best regards,  
**Cherine Joseph**  
Security Analyst  
Governance, Risk, and Compliance
