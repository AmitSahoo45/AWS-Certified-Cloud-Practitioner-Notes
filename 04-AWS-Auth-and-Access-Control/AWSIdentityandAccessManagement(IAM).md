### AWS IAM Notes:

1. **IAM Overview**:
   - IAM stands for Identity and Access Management.
   - Used for authentication and authorization in AWS.
   - Principals (users, applications) must be authenticated to send requests.
   - Principles of authentication and authorization ensure secure access to AWS resources.

2. **Authentication and Authorization**:
   - Authentication: Proving identity (e.g., password, multi-factor authentication).
   - Authorization: Granting or denying access to resources based on policies.

3. **Core Components of IAM**:
   - Users: Represent individuals or applications with access to AWS.
   - User Groups: Collection of users with common permissions.
   - Roles: Used for delegation and assumed by entities to gain permissions.
   - Policies: Define permissions for identities or resources (identity-based, resource-based).

4. **IAM Users**:
   - Root User: Full access, not recommended for regular use due to security risks.
   - IAM User: Created with specific permissions, can log in via console, CLI, API.
   - Amazon Resource Name (ARN): Unique identifier for AWS resources like users.

5. **User Groups**:
   - Used for simplified management of permissions for multiple users.
   - Permissions policies applied to groups, users inherit permissions from groups.

6. **Authentication Methods**:
   - Username and Password: Used with multi-factor authentication for enhanced security.
   - Access Keys: ID and secret key used for programmatic access via CLI or API.
   - Security Token Service (STS): Generates short-term credentials for temporary access.

7. **Root User vs. IAM User**:
   - Root User: Full access, difficult to restrict, not recommended for regular use.
   - IAM User: Assigned permissions through policies, best practice for day-to-day access.

8. **Best Practices**:
   - Use IAM Users instead of Root User for regular access.
   - Apply least privilege principle by granting minimum necessary permissions.
   - Enable multi-factor authentication (MFA) for enhanced security.
   - Regularly review and update permissions policies.