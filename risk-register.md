#AutoFix Workshop - Risk Register
This register identifies key cyber and physical threats to AutoFix Workshop, based on the asset inventory completed in the previous task. Each risk is scored by likelihood and impact, with recommended controls mapped to the NIST Cybersecurity Framework (CSF).

| # | Threat | Vulnerable Asset(s) | Likelihood | Impact | Risk Level | Mitigation Control | NIST CSF Category |
|---|--------|---------------------|-----------|--------|-----------|---------------------|---------------------|
| 1 | Ransomware infection | Back Office Laptop (QuickBooks, payroll) | Medium | High | High | Offline/cloud backups; endpoint antivirus; restrict admin rights | Protect / Recover |
| 2 | Unauthorized access to customer records | Booking App, Customer Contact Records | Medium | High | High | Strong passwords + MFA on booking app; limit access to receptionist/owner | Protect |
| 3 | Card skimming / payment fraud | POS Card Reader | Low | High | Medium | PCI-compliant terminal; inspect device regularly for tampering | Protect |
| 4 | Wi-Fi intrusion via guest network | Office Wi-Fi Router, Front Desk PC | Medium | Medium | Medium | Segment guest Wi-Fi from business network; disable inter-device access | Protect |
| 5 | Cloud service outage (booking/QuickBooks down) | Booking App, QuickBooks | Medium | Medium | Medium | Local backup/export of key data; manual paper fallback during outages | Recover |