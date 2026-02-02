# Scope and Tiering Model

## Primary Driver: Data Sensitivity

Classify vendors based on the most sensitive data they access or store:
- None
- Internal Business Data
- PII
- PHI
- Financial Reporting Data (SOX)

## Secondary Drivers

Access Level:
- No integration
- SSO only
- API integration
- Privileged or admin integration

Operational Criticality:
- Low
- Medium
- High

## Tier Rules

High Risk if any apply:
- Accesses PII, PHI, or financial reporting data
- Uses API or privileged integration
- Provides mission critical services

Medium Risk if:
- Accesses internal business data
- Uses SSO only
- Important but not mission critical

Low Risk if:
- No sensitive data exposure
- No integration
- Non critical services

