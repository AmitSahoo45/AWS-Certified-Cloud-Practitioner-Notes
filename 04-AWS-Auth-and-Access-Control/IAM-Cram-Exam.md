### AWS IAM Cram Exam Notes:

1. **IAM Overview**:
   - IAM is a Web service for controlling access to AWS resources securely.
   - Manages authentication (who is signed in) and authorization (what permissions they have).

2. **IAM Components**:
   - Users: Individual accounts for logging in; have no permissions by default.
   - Groups: Organize users and apply policies for permissions.
   - Policies: Define permissions; applied to users or groups.
   - Roles: Delegate permissions assumed by services.

3. **Access Methods**:
   - Users log in with a username/password for AWS Management Console.
   - For programmatic access, use access keys (Access ID + Secret Access Key) for CLI/API.

4. **Root User and Multi-Factor Authentication (MFA)**:
   - Root User: Created account user with full permissions; login with email used for signup.
   - MFA adds a second factor (like a code) for enhanced security.

5. **Service Control Policies (SCP)**:
   - Define maximum permissions in an account, used in AWS Organizations.

6. **IAM Best Practices**:
   - Lock away root user access keys; avoid sharing user accounts.
   - Create individual IAM users; use groups for permissions assignment.
   - Grant least privilege; only provide necessary rights.
   - Start with AWS managed policies for ease and security.
   - Use customer managed policies over inline policies for better management.
   - Review IAM permissions regularly; ensure users have required access.
   - Configure strong password policy and enable MFA for enhanced security.
   - Use roles for applications on EC2 instances; avoid sharing access keys.
   - Rotate credentials regularly; change access keys and passwords periodically.
   - Remove unnecessary credentials and monitor account activity for security.