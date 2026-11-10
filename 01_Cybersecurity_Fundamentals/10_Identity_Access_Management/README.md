
# Identity and Access Management (IAM) Laboratory

## 1. Overview

This laboratory demonstrates fundamental Identity and Access Management (IAM) concepts and the importance of controlling access to organizational resources.

## 2. Objectives

- Understand Identity and Access Management.
- Differentiate authentication and authorization.
- Apply the Principle of Least Privilege.
- Understand Role-Based Access Control (RBAC).
- Identify common authentication methods.
- Understand Multi-Factor Authentication (MFA).

## 3. Scenario

A company needs to manage access for its employees within a cloud environment.

The administrator must create individual user accounts, organize users into groups and assign permissions according to their responsibilities.

## 4. IAM Concepts

### Authentication

Authentication verifies the identity of a user.

Example:
- Username and password.
- Biometric authentication.
- Multi-Factor Authentication (MFA).

### Authorization

Authorization determines which resources and actions an authenticated user is allowed to access.

Example:
- Read files.
- Modify documents.
- Access administrative resources.

### Principle of Least Privilege

Users should receive only the minimum permissions necessary to perform their jobs.

## 5. Simulated IAM Configuration

| Component | Configuration |
|---|---|
| User | Alex1 |
| Group | G1 |
| Environment | AWS IAM |
| Access Model | Role-Based Access Control |
| Security Principle | Least Privilege |

## 6. Access Control Models

### DAC - Discretionary Access Control

Resource owners determine who can access their resources.

### MAC - Mandatory Access Control

Access is determined by centralized security policies and classifications.

### RBAC - Role-Based Access Control

Permissions are assigned according to organizational roles.

### ABAC - Attribute-Based Access Control

Access decisions are based on attributes such as department, location or job function.

## 7. Recommended Security Practices

1. Create unique accounts for every user.
2. Assign users to appropriate groups.
3. Apply the Principle of Least Privilege.
4. Enable Multi-Factor Authentication.
5. Review permissions regularly.
6. Disable inactive accounts.
7. Monitor authentication activity.
8. Protect privileged accounts.

## 8. Common IAM Threats

| Threat | Description |
|---|---|
| Credential Theft | Unauthorized access through stolen credentials |
| Privilege Escalation | Obtaining permissions beyond authorized levels |
| Account Compromise | Unauthorized control of a user account |
| Password Attacks | Attempts to discover or guess passwords |
| Insider Threat | Misuse of legitimate access |

## 9. Security Recommendations

- Use strong passwords.
- Enforce MFA.
- Apply least privilege.
- Monitor access logs.
- Conduct periodic access reviews.
- Remove unnecessary permissions.
- Use separate administrative accounts.

## 10. Key Findings

Effective IAM reduces unauthorized access and limits the impact of compromised accounts.

Assigning permissions through groups simplifies administration and improves consistency.

## 11. Conclusion

Identity and Access Management is essential for protecting organizational systems and sensitive information.

Proper authentication, authorization and access control help reduce security risks.

## 12. Skills Demonstrated

- Identity and Access Management
- Authentication and authorization
- AWS IAM fundamentals
- Role-Based Access Control
- Principle of Least Privilege
- Multi-Factor Authentication
- Access management
