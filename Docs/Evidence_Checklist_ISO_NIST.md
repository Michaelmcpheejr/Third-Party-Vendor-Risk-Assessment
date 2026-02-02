# Vendor Evidence Checklist (ISO 27001 + NIST Mapped)

This checklist defines the standard evidence artifacts required to validate third party vendor security controls. It supports audit defensibility, framework alignment, and remediation tracking for SaaS focused TPRM.

---

## Standard Vendor Evidence Package

| Evidence Item | Required Tier | What it Proves | Common Red Flags | ISO 27001 Reference | NIST SP 800-53 Reference | Remediation Expectations |
|--------------|--------------|----------------|------------------|---------------------|--------------------------|--------------------------|
| SOC 2 Type II Report or ISO 27001 Certificate | High, Medium | Vendor has undergone independent security assurance testing | Type I only, outdated report, major exceptions | A.5, A.8 | CA-2 | Require updated report, bridge letter, or compensating controls |
| Information Security Policy or Program Overview | High, Medium | Vendor has formal governance and leadership accountability | No written program, policies not reviewed annually | A.5 | PM-1 | Vendor must provide governance documentation or security attestation |
| Encryption at Rest and in Transit Statement | High, Medium | Sensitive data is protected during storage and transmission | Backups not encrypted, weak protocols | A.8 | SC-13 | Require encryption implementation or compensating safeguards |
| MFA Enforcement for Privileged/Admin Access | High | Privileged accounts are protected from credential compromise | MFA optional or inconsistent | A.9 | IA-2 | Must enforce MFA prior to onboarding approval |
| Incident Response Plan + Customer Notification SLA | High, Medium | Vendor can respond and communicate effectively during incidents | No notification timeline, unclear escalation | A.16 | IR-1 | Add contractual breach notification clauses and IR commitments |
| Disaster Recovery / Business Continuity Summary (RTO/RPO) | High | Vendor can maintain availability and recover operations | No DR testing, undefined recovery objectives | A.17 | CP-2 | Require DR testing evidence or resilience commitments |
| Penetration Test or Vulnerability Assessment Summary | High | Vendor identifies and remediates security weaknesses proactively | No external testing, critical findings unresolved | A.12 | RA-5 | Require remediation plan for critical vulnerabilities |
| Subprocessor List + Fourth Party Oversight Model | High, Medium | Vendor manages downstream third party risk | Unknown subprocessors, no oversight | A.15 | SR-3 | Require transparency and contractual subprocessor controls |
| Data Retention and Secure Deletion Policy | High, Medium | Vendor can securely dispose of sensitive data at termination | No deletion guarantees, undefined retention | A.8 | MP-6 | Require contractual deletion and retention enforcement |
| Executive Risk Acceptance Approval (Exceptions Only) | High (Exceptions) | Leadership formally accepts residual vendor risk | Informal acceptance with no documentation | A.5 | PM-9 | Require documented sign off before proceeding |

---

## Notes

- High Risk vendors must provide the full evidence package before approval.
- Medium Risk vendors provide standard assurance evidence with limited deep dive.
- Low Risk vendors may require only minimal attestation depending on scope.
- Any missing evidence results in remediation tracking or formal risk acceptance.

