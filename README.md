# Hospital Security Review

**WGU D486 · Governance, Risk, and Compliance · Task 1**

I played the CISO of Fielder Medical Center. An outside firm audited the hospital's new system for doctors' license files, which hold names, home addresses and Social Security numbers. Government auditors also need access to it to keep federal funding flowing. My job was to review the audit, judge the risks and write the fix plan.

## What I reviewed

Five security controls from NIST SP 800-53 Rev. 5, under FISMA:

| Control | What it means | Example fix |
|---|---|---|
| AC-6 | Least privilege | Role-based access and MFA |
| CA-5 | Plan of action and milestones | A formal tracked fix plan (POA&M) |
| CA-7 | Continuous monitoring | SIEM and vulnerability scanners |
| RA-3 | Risk assessment | Re-assess after every major change |
| RA-7 | Risk response | A formal process for handling risks |

For each one: the risk level, the impact, and the tools, policy and staff changes needed to fix it.

## Payment card policy

The hospital also started selling medical equipment through a new point-of-sale system. I wrote a PCI DSS policy for it: firewalls and network separation, removing default vendor passwords, and antivirus monitoring, with clear roles for IT, security and leadership.

## Files

- `DFN1_Task1_Security_System_Evaluation_and_Remediation.pdf`: the full report

**Topics:** NIST 800-53, FISMA, PCI DSS, risk assessment, security policy
