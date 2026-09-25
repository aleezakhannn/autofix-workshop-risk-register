## AutoFix Workshop - Risk Register

This register identifies key cyber and physical threats to AutoFix Workshop, based on the asset inventory completed in the previous task. Each risk is scored by likelihood and impact, with recommended controls mapped to the NIST Cybersecurity Framework (CSF).

| # | Threat | Vulnerable Asset(s) | Likelihood | Impact | Risk Level | Mitigation Control | NIST CSF Category |
|---|--------|---------------------|-----------|--------|-----------|---------------------|---------------------|
| 1 | Ransomware infection on a key workstation | Back Office Laptop (QuickBooks, payroll) | Medium | High | High | Maintain regular backups (cloud and offline), keep antivirus active, and limit admin rights to necessary users | Protect / Recover |
| 2 | Unauthorized access to customer contact records | Booking App, Customer Contact Records | Medium | High | High | Enable MFA on the booking app and restrict access to the receptionist and owner only | Protect |
| 3 | Card skimming at the point of sale | POS Card Reader | Low | High | Medium | Use a PCI-compliant terminal and inspect it periodically for signs of tampering | Protect |
| 4 | Intrusion into the business network via guest Wi-Fi | Office Wi-Fi Router, Front Desk PC | Medium | Medium | Medium | Segment guest Wi-Fi onto a separate network with no access to business devices | Protect |
| 5 | Unplanned outage of the booking app or QuickBooks | Booking App, QuickBooks | Medium | Medium | Medium | Keep an exported copy of key data and maintain a simple manual fallback process for outages | Recover |

## Limitations

This register focuses on the most likely risks based on the current asset inventory. It doesn't cover every possible scenario (e.g., insider threats or natural disasters), and likelihood/impact scores are estimates rather than data-driven calculations, since no formal risk assessment tooling was used.
