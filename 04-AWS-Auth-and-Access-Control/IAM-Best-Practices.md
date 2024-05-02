### IAM Best Practices Notes:

1. **Federation with Identity Provider (IdP)**:
   - Recommend using federation with an Identity Provider (IdP) for human users accessing AWS.
   - Encourages using temporary credentials via IAM Identity Center or Federation for enhanced security.

2. **Temporary Credentials with IAM Roles**:
   - Workloads should utilize IAM roles and temporary credentials instead of storing access keys.
   - Applications should be configured to use roles for improved security through the Security Token Service (STS).

3. **Multi-Factor Authentication (MFA)**:
   - Enforce multi-factor authentication (MFA) for all accounts, including root and privileged accounts.
   - Regularly rotate access keys for enhanced security, especially for long-term credentials.

4. **Root User Management**:
   - Safeguard root user credentials by setting complex passwords, enabling MFA, and limiting usage.
   - Avoid using root user credentials for everyday tasks, lock them away securely.

5. **Least Privilege Principle**:
   - Apply the least privilege principle to all users and applications, granting only necessary permissions.
   - Start with AWS managed policies and transition towards custom policies to achieve least privilege.

6. **IAM Access Analyzer**:
   - Utilize IAM Access Analyzer to generate least privileged policies based on actual access activity.
   - Regularly review and remove unused users, roles, permissions, policies, and credentials for cleanup.

7. **Use Conditions in IAM Policies**:
   - Use conditions in IAM policies to further restrict access based on specific criteria like IP addresses.
   - Implement conditions to ensure access is granted only from authorized locations or conditions.

8. **IAM Access Analyzer for Verification**:
   - Verify public and cross-account access to resources using IAM Access Analyzer.
   - Ensure only appropriate permissions are granted and validate IAM policies for security and functionality.

9. **Establish Guardrails Across Multiple Accounts**:
   - Implement permissions boundaries to delegate permissions management within accounts.
   - Use AWS Organizations and AWS Control Tower to establish security measures across multiple AWS accounts.
   - Permissions boundaries limit the maximum permissions a user can have, preventing over-privileged access.