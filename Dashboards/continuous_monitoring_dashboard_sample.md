# Continuous Monitoring Dashboard Sample (High Risk Vendors)

## Purpose

This dashboard represents how High Risk SaaS vendors may be monitored continuously between annual assessments. The goal is to detect early warning signals such as security posture degradation, breach intelligence, or overdue remediation items.

This is especially important for vendors handling sensitive data (PII, PHI, PCI, SOX-relevant data).

---

## Monitoring Summary (Leadership View)

- Total High Risk Vendors: 12  
- Vendors with Open Critical Findings: 3  
- Vendors with SOC 2 Expiring in < 90 Days: 2  
- Vendors with Recent Breach Alerts: 1  
- Remediation Items Past Due: 4  

---

## Key Monitoring Signals

High Risk vendors may be monitored for:

- External security posture rating changes (BitSight/SecurityScorecard-style)
- Breach or threat intelligence alerts
- SOC 2 or ISO certification expiration tracking
- Subprocessor (fourth party) changes
- Incident notification SLA compliance
- Open remediation findings trending past due

---

## Sample Monitoring Table (Non-Technical Friendly)

| Vendor Name        | Security Posture Last Month | Security Posture Now | Status        | Action Required                     |
|-------------------|-----------------------------|----------------------|--------------|-------------------------------------|
| CloudHR SaaS      | Strong                       | Moderate Decline     | Escalate     | Request remediation plan and review |
| FinanceCloud ERP  | Moderate                     | Moderate             | Monitor      | Continue quarterly oversight        |
| WorkChat Platform | Strong                       | Strong               | Stable       | No action needed                    |
| DataAnalytics Pro | Moderate                     | High Concern         | High Risk    | Trigger reassessment immediately    |

---

## Reviewer Note

Security posture monitoring provides an additional layer of assurance beyond questionnaires. It helps organizations detect changes in vendor risk between formal review cycles and supports proactive escalation before incidents occur.
