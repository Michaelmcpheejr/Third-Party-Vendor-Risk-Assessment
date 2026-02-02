# Extended Vendor Security Questionnaire (High Risk Vendors Only)

## Purpose

This extended questionnaire is required for **High Risk vendors** that handle sensitive data (PII, PHI, PCI, SOX financial data) or maintain privileged/API integrations. It supports deeper validation of vendor security posture beyond the Core 15.

This module is designed to assess high assurance controls across identity, infrastructure, application security, incident response, and resilience.

---

## Section 1: Governance and Security Program (Questions 1–5)

1. Do you have a designated security leader (CISO or equivalent) responsible for your security program?

2. How often are security policies reviewed and approved by executive leadership?

3. Do you maintain a formal risk management process for identifying and mitigating security risks?

4. Do you provide security awareness training to all employees at least annually?

5. Do you conduct background checks for employees with access to sensitive systems or customer data?

Evidence Examples:
- Security governance overview
- Training completion metrics
- HR screening policy

---

## Section 2: Identity and Access Management (Questions 6–10)

6. Do you enforce MFA for all privileged and administrative access without exception?

7. Do you implement role-based access control (RBAC) for all production systems?

8. Are privileged accounts separated from standard user accounts (no shared admin credentials)?

9. Do you log and monitor all privileged access activity?

10. Do you perform access reviews for privileged accounts at least quarterly?

Evidence Examples:
- Access control policy
- Privileged access logs
- Review attestations

---

## Section 3: Data Protection and Encryption (Questions 11–15)

11. Is all customer data encrypted at rest using industry standard encryption (AES-256 or equivalent)?

12. Is all customer data encrypted in transit using TLS 1.2+?

13. Do you maintain encryption key management practices (rotation, protection, restricted access)?

14. Do you support customer-managed keys (BYOK or HYOK) for high sensitivity clients if required?

15. Do you maintain documented data classification and handling procedures?

Evidence Examples:
- Key management documentation
- Encryption architecture excerpt
- Data classification policy

---

## Section 4: Vulnerability and Patch Management (Questions 16–20)

16. Do you perform regular vulnerability scanning of production systems?

17. How quickly are critical vulnerabilities remediated (example: within 15–30 days)?

18. Do you conduct annual third party penetration testing?

19. Do you maintain a formal vulnerability disclosure or bug bounty program?

20. Are security findings tracked through remediation to closure?

Evidence Examples:
- Vulnerability management policy
- Pen test executive summary
- Remediation tracker samples

---

## Section 5: Secure Development and Change Control (Questions 21–24)

21. Do you maintain a Secure SDLC program with security embedded into development practices?

22. Are code changes reviewed and approved prior to deployment into production?

23. Do you perform security testing such as SAST/DAST before major releases?

24. Do you maintain separation between development, staging, and production environments?

Evidence Examples:
- SDLC documentation
- Change management workflow
- Security testing reports

---

## Section 6: Incident Response and Monitoring (Questions 25–28)

25. Do you maintain a documented Incident Response Plan that is tested at least annually?

26. What is your defined customer notification SLA following a confirmed breach?

27. Do you provide post-incident reporting including root cause and corrective actions?

28. Do you maintain centralized security monitoring (SIEM or equivalent) with alerting for critical events?

Evidence Examples:
- IR plan excerpt
- Tabletop exercise summary
- Monitoring and logging overview

---

## Section 7: Business Continuity and Third Party Oversight (Questions 29–30)

29. Do you maintain tested Disaster Recovery and Business Continuity plans with defined RTO/RPO?

30. Do you assess and monitor your subprocessors (fourth parties) for security risk, and can you provide transparency into their role?

Evidence Examples:
- DR test summary
- Subprocessor inventory
- Oversight and contract controls

---

## Completion Notes

High Risk vendors must provide supporting evidence for responses above. Any gaps may result in:

- Remediation requirements prior to approval  
- Conditional onboarding decisions  
- Formal risk acceptance with executive sign-off  

This questionnaire supports audit-ready vendor assurance aligned to ISO 27001 and NIST SP 800-53 expectations.
