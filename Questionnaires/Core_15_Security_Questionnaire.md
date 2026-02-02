# Core Security Questionnaire (15 Questions)

## Section 1: Company and Compliance

1. Do you maintain a current SOC 2 Type II report, ISO 27001 certification, or equivalent independent audit?
2. Do you have a documented Information Security Program approved by leadership?
3. Have you experienced a security incident or breach in the last 24 months? If yes, provide impact, remediation actions, and business continuity outcomes.

## Section 2: Data Protection and Privacy

4. What categories of data will you store, process, or transmit? (None, Internal, PII, PHI, PCI, Financial Reporting Data)
5. Is sensitive data encrypted at rest and in transit?
6. Do you support data retention and secure deletion upon contract termination?
7. Do you have a privacy program aligned to applicable regulations?

## Section 3: Identity and Access Control

8. Do you enforce MFA for all administrative and privileged access?
9. Do you support SSO integration (SAML or OIDC) and role based access controls?
10. Do you perform periodic access reviews for privileged accounts internally?

## Section 4: Security Operations and Resilience

11. Do you maintain centralized logging and monitoring for security events?
12. Do you have an incident response plan and customer notification SLAs?
13. Do you maintain DR and BCP plans with tested recovery objectives (RTO and RPO)?

## Section 5: Vendor Management and Assurance

14. Do you use subprocessors or fourth parties, and do you assess them for security risk?
15. Can you provide required evidence artifacts for high risk onboarding (SOC2 or ISO, IR, DR, pen test summary)?

## Trigger for Extended Module

Extended module is required if any apply:
- No SOC2 or ISO equivalent
- No encryption
- No MFA for admin access
- Incident response or notification SLA gaps
- Handles PHI, PCI, or financial reporting data
- High risk integration (API or privileged)
