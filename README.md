## Environment Overview

This setup is designed to create a secure, scalable, and compliant AWS environment while simplifying multi-account management. Key Components:

1. **AWS Control Tower & Organizations**
   - Automates multi-account setup with governance guardrails.
   - Ensures consistency and compliance across all accounts.

2. **Symmetric Encryption Keys (AWS KMS)**
   - Protects sensitive data with encryption at rest and in transit.
   - Simplifies key management and access control for compliance.

3. **API Logging (AWS CloudTrail)**
   - Tracks all user and service activity for visibility and auditing.
   - Centralizes logs for efficient monitoring and incident response.

4. **Least Privilege Roles**
   - Isolates critical functions (e.g., billing) to reduce risks.
   - Minimizes the impact of accidental or malicious changes.

5. **Security Hub with AWS Config**
   - Monitors for misconfigurations and ensures compliance with standards.
   - Automates detection and remediation for faster response to issues.

6. **Single Sign-On (AWS SSO)**
   - Simplifies user access to multiple accounts with a single login.
   - Enhances security by integrating with enterprise-grade IdPs (e.g., Entra ID).
