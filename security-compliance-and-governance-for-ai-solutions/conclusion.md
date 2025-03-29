---
title: Conclusion
parent: 8. Security, Compliance, and Governance for AI Solutions
nav_order: 7
---

# Conclusion
{: .no_toc }

<details open markdown="block">
  <summary>
    Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Defense in depth layers and associated AWS services
1. Data protection
  - Data at rest - AWS KMS or customer managed key
  - Data in transit - ACM and AWS Private CA
2. Identity and access management
  - AWS IAM.
3. Application protection
  - AWS Shield, AWS Cognito and Others
4. Network and edge protection
  - Amazon VPC, AWS WAF
5. Infrastructure protection
  - IAM, IAM user groups and network ACLs
6. Threat detection and incident response
  - threat detection - AWS Security Hub, AWS GuardDuty
  - incident response - AWS Lambda, Amazon EventBridge
7. Policies, procedures, and awareness
  - AWS IAM Access Analyzer

{% include security-compliance-and-governance-for-ai-solutions/conclusion.md %}
