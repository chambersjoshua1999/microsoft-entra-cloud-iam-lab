# microsoft-entra-cloud-iam-lab
Hands-on Microsoft Entra ID and Cloud IAM security lab covering user provisioning, group management, MFA, Conditional Access, and identity security monitoring.
# Microsoft Entra ID — Cloud IAM Security Lab

## Project Overview

This project is a hands-on Identity and Access Management (IAM) lab built using Microsoft Entra ID. The purpose is to gain practical experience managing cloud identities, configuring access controls, and implementing security practices within a simulated enterprise environment.

The lab demonstrates fundamental IAM concepts and cloud security administration through practical exercises, documentation, and testing.

## Project Objectives

- Understand cloud-based Identity and Access Management.
- Create and manage user identities.
- Organize users into security groups.
- Understand authentication and authorization.
- Implement Multi-Factor Authentication (MFA).
- Configure Conditional Access policies.
- Explore Role-Based Access Control (RBAC).
- Monitor identity activity and sign-in logs.
- Understand identity governance and access management.

## Technologies & Tools

| Technology | Purpose |
|---|---|
| Microsoft Entra ID | Cloud identity management |
| Microsoft Azure | Cloud platform |
| GitHub | Project documentation and version control |
| Microsoft Graph | Identity management automation (planned) |
| Python | IAM automation (planned) |

## Lab Environment

A simulated enterprise environment was created using fictional employee accounts to practice identity administration and access management.

Current environment:
- 12 user accounts created.
- Individual user profiles configured.
- Security groups created.
- Group membership reviewed.
- User properties and assigned roles explored.

## Project Labs

#### Lab A – User and Group Management


## Objective
Practice identity administration using Microsoft Entra ID by creating users, organizing accounts into security groups, and managing group memberships.

## Environment
- Platform: Microsoft Entra ID
- Environment: Test tenant
- Accounts: 12 fictional test users

## Tasks Completed

1. Created a Microsoft Entra ID tenant.
2. Created 12 fictional user accounts.
3. Configured user account profiles.
4. Created security groups.
5. Assigned users to appropriate security groups.
6. Reviewed group membership and user account configurations.

## Security Concepts Learned

- User provisioning
- Identity lifecycle management
- Security groups
- Group-based access management
- Centralized identity administration
- Least privilege access

## Testing and Validation

Verified that the test accounts appeared in the user directory and that group memberships were correctly assigned.

## Evidence

See the `/screenshots` directory for configuration screenshots.

## Results

Successfully completed the initial user provisioning and group management exercises in Microsoft Entra ID.

### Lab B — Multi-Factor Authentication & Conditional Access

Project Overview

This lab explores authentication security and identity protection using Microsoft Entra ID.

The objective was to configure and investigate Multi-Factor Authentication (MFA), register Microsoft Authenticator, test number matching, and review sign-in logs to understand how organizations protect employee accounts.

The lab uses a fictional organization, Chambers Corporation, and a dedicated test account.

B1 — Security Defaults

Objective

Enable Microsoft's built-in identity security protections.

Activities

Accessed Microsoft Entra tenant properties.

Located Security Defaults.

Enabled Security Defaults.

Reviewed the purpose of built-in security protections.

Real-World Application

Security Defaults provide a baseline level of identity protection by helping organizations enforce stronger authentication requirements.

Status

Completed.

B2 — Authentication Methods

Objective

Understand and review the authentication methods available to organizational users.

Activities

Reviewed Microsoft Entra authentication methods.

Located Microsoft Authenticator configuration.

Reviewed authentication method availability.

Investigated how users register authentication methods.

Real-World Application

IAM administrators manage authentication methods to ensure employees use approved and secure ways to verify their identities.

Status

Reviewed and documented.

B3 — Microsoft Authenticator Registration

Objective

Register Microsoft Authenticator for a dedicated test account.

Test Account

Bob.Dale.Test

Activities

Opened the test account's authentication registration process.

Registered Microsoft Authenticator.

Connected the account to the Authenticator application on an iPhone.

Verified the registered authentication method.

Real-World Application

Organizations use authenticator applications to provide an additional layer of protection beyond passwords.

Status

Completed.

B4 — Number Matching

Objective

Test number matching as an additional authentication security measure.

Activities

Initiated a sign-in using Bob.Dale.Test.

Received a number-matching authentication challenge.

Opened Microsoft Authenticator.

Entered the displayed number, 74.

Successfully approved the authentication request.

Real-World Application

Number matching helps reduce accidental authentication approvals and MFA fatigue attacks.

Status

Completed.

B5 — Sign-in Logs and Authentication Details

Objective

Investigate authentication activity using Microsoft Entra sign-in logs.

Activities

Opened the Microsoft Entra sign-in logs.

Located authentication events for Bob.Dale.Test.

Reviewed successful sign-in results.

Inspected Authentication Details.

Investigated authentication status and previously satisfied requirements.

Observations

The reviewed event displayed:

Succeeded: True

Previously satisfied: True

First factor requirement

A successful sign-in confirms that authentication succeeded, but a previously satisfied requirement does not independently establish that a new MFA challenge occurred during that particular event.

Real-World Application

Security and IAM analysts use sign-in logs to investigate authentication failures, suspicious sign-ins, and potential account compromise.

Status

Completed — log review performed.

B6 — Fresh MFA Verification

Objective

Verify that MFA is enforced during a fresh authentication session.

Testing Procedure

Open a private browser session.

Sign in using the dedicated test account.

Complete the initial authentication step.

Check whether an MFA challenge is presented.

Complete the Authenticator verification.

Review the corresponding sign-in event.

Inspect Authentication Details to confirm the MFA result.

Expected Evidence

A fresh sign-in event showing successful MFA authentication.

Status

Pending final fresh sign-in verification.

Conditional Access — Additional Learning

Conditional Access allows organizations to create policies that evaluate sign-in conditions before granting access.

Examples include:

Requiring MFA for specific applications.

Blocking access from specified locations.

Requiring compliant devices.

Applying additional authentication requirements based on risk.

Custom Conditional Access policies generally require Microsoft Entra ID P1 or an eligible licensing arrangement.

This lab used Security Defaults rather than custom Conditional Access policies because the available tenant did not have the required subscription.

Security Defaults and Conditional Access are different security approaches and should not be represented as the same configuration.

Technologies and Concepts

Microsoft Entra ID

Multi-Factor Authentication

Microsoft Authenticator

Number Matching

Security Defaults

Conditional Access

Authentication Methods

Sign-in Logs

Authentication Details

Identity Protection

Skills Demonstrated

Authentication method administration

MFA registration and testing

Number-matching verification

Authentication troubleshooting

Sign-in log investigation

Identity security configuration

Understanding Conditional Access

Project Limitations

Custom Conditional Access policies were not deployed because the tenant did not have the required licensing.

Fresh MFA verification remains a final evidence item until confirmed through a new sign-in event.

Conclusion

This lab demonstrates foundational knowledge of identity authentication and account security using Microsoft Entra ID.

The exercises provide practical experience with MFA registration, number matching, authentication monitoring, and sign-in investigation.

These skills are relevant to entry-level IAM Analyst, Identity Administrator, and Security Analyst positions.

### Lab C — Role-Based Access Control (RBAC)

**Status: Planned**

- Explore Microsoft Entra roles.
- Understand Azure RBAC.
- Review role assignments.
- Apply least-privilege principles.

### Lab D — Enterprise Applications & SSO

**Status: Planned**

- Explore enterprise applications.
- Understand Single Sign-On (SSO).
- Review application permissions.
- Learn identity federation fundamentals.

### Lab E — Identity Governance

**Status: Planned**

- Explore access reviews.
- Understand user access lifecycle management.
- Review group-based access.
- Learn identity governance principles.

### Lab F — Identity Monitoring & Sign-In Logs

**Status: Planned**

- Review sign-in logs.
- Examine authentication activity.
- Identify unsuccessful sign-in attempts.
- Understand identity-related security monitoring.

### Lab G — Microsoft Graph & Python Automation

**Status: Planned**

- Explore Microsoft Graph API.
- Learn how to retrieve user information.
- Practice identity management automation.
- Document automation workflows.

## Repository Structure

```
