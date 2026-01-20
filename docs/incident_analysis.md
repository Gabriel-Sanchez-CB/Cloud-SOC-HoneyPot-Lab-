## Security Recommendations
Based on the observed brute-force activity, the following defensive measures are recommended:

- Enable Multi-Factor Authentication (MFA) for all remote access
- Restrict RDP access using Network Security Group (NSG) rules
- Implement account lockout policies after multiple failed attempts
- Create Microsoft Sentinel analytics rules to alert on brute-force patterns
- Continuously monitor authentication logs for anomalous behavior
  
For more information on related attack techniques, refer to the MITRE ATT&CK framework: https://attack.mitre.org
