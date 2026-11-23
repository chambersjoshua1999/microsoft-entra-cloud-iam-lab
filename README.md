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

## Lab A — User and Group Management

## 1. Project Overview

**Lab Name:** User and Group Management  
**Platform:** Microsoft Entra ID  
**Project:** Cloud IAM Security Lab  
**Organization:** Chambers Corporation (Fictional Organization)  
**Status:** Completed

### Objective

The objective of this lab was to establish a centralized identity management environment using Microsoft Entra ID.

I created fictional employee accounts, organized users into security groups, configured group membership, and reviewed individual user profiles.

This lab demonstrates how organizations manage employee identities and organize access through centralized identity management.

### Business Scenario

Chambers Corporation is a fictional organization with employees across multiple departments, including:

- Information Technology (IT)
- Developers
- Human Resources (HR)
- Finance

The organization needs a centralized way to manage employee accounts and organize users based on their departments and responsibilities.

**The primary security goals were:**

- Establish centralized user management.
- Organize employees into appropriate security groups.
- Improve access management through group membership.
- Separate employees based on departmental responsibilities.
- Establish a foundation for role-based access control (RBAC).
- Support the principle of least privilege.

---

## 2. Tools and Technologies

The following tools and technologies were used throughout this lab:

- **Microsoft Entra ID:** Cloud-based identity and access management platform.
- **Microsoft Entra Admin Center:** Administrative portal used to manage users and groups.
- **User Accounts:** Fictional employee identities created for testing.
- **Security Groups:** Groups used to organize users based on departments and responsibilities.
- **Group Membership:** Used to associate employee accounts with the appropriate security groups.

---

## 3. Implementation

### A1 — User Directory Creation

**Objective:** Create a centralized directory containing fictional employee accounts.

**Actions Performed:**

- Created a Microsoft Entra ID tenant for the lab environment.
- Navigated to the Users section in Microsoft Entra Admin Center.
- Created 12 fictional employee accounts.
- Configured individual user information.
- Verified that the accounts appeared in the user directory.

**Why This Matters:**

Organizations need a centralized directory to manage employee identities.

Instead of managing individual accounts across different systems, administrators can use Microsoft Entra ID to maintain a centralized identity directory.

**Real-World Application:**

In an enterprise environment, IT administrators create employee accounts when someone joins the organization. These accounts become the foundation for assigning application access, security groups, and permissions.

**Evidence:**

`screenshots/Lab-A/A1-user-directory.png`

### A2 — Individual User Profile Configuration

**Objective:** Review individual user profiles and understand how employee identities are configured.

**Actions Performed:**

- Selected an individual fictional employee account.
- Reviewed the user's profile information.
- Examined available account configuration options.
- Reviewed the identity information associated with the account.

**Why This Matters:**

User profiles contain important identity information that administrators use to manage employees.

Understanding user profiles is important when troubleshooting account issues, managing employee information, and maintaining accurate identity records.

**Real-World Application:**

An IAM administrator may review a user profile when an employee cannot access an application, changes departments, or requires an account update.

**Evidence:**

`screenshots/Lab-A/A2-user-profile.png`

### A3 — Security Group Creation

**Objective:** Create security groups to organize employees according to their departments and responsibilities.

**Actions Performed:**

- Navigated to the Groups section in Microsoft Entra Admin Center.
- Created security groups for the fictional organization.
- Organized groups around departmental responsibilities.
- Reviewed the created groups.

**Why This Matters:**

Security groups simplify identity and access management.

Instead of assigning permissions individually to every employee, administrators can manage access through groups.

This makes it easier to maintain consistent access policies as an organization grows.

**Real-World Application:**

An organization may have separate groups for IT, HR, Finance, and Developers.

When an employee joins a department, an administrator can add that employee to the appropriate group instead of managing every permission individually.

**Evidence:**

`screenshots/Lab-A/A3-security-groups.png`

### A4 — Group Membership Configuration

**Objective:** Assign fictional employee accounts to the appropriate security groups.

**Actions Performed:**

- Opened the security groups created in the previous step.
- Added the appropriate fictional employee accounts to each group.
- Reviewed group membership.
- Verified that users appeared in their assigned groups.

**Why This Matters:**

Group membership establishes an organized way to manage identities and supports centralized access administration.

It also creates the foundation for assigning permissions based on job responsibilities.

**Real-World Application:**

When an employee joins the Finance department, an IAM administrator can add the employee to the Finance security group.

When an employee transfers departments, their group membership can be updated to reflect their new responsibilities.

**Security Benefit:**

Proper group membership helps organizations maintain access separation and reduces the need for manually managing permissions for every individual employee.

**Evidence:**

`screenshots/Lab-A/A4-group-membership.png`

### A5 — Group Configuration Review

**Objective:** Review security group configurations and understand the available membership settings.

- **Assigned Membership:** Administrators manually add and remove users.
- **Dynamic User Membership:** Users are automatically added or removed based on configured user attributes and rules.

**Evidence:**

`screenshots/Lab-A/A5-group-configuration.png`

---

## 4. Security Concepts Demonstrated

This lab introduced several foundational Identity and Access Management concepts.

| Concept | Description |
|---|---|
| Identity Management | Creating and managing employee identities. |
| Microsoft Entra ID | Centralized cloud identity management. |
| Security Groups | Organizing users based on responsibilities. |
| Group Membership | Managing which users belong to specific groups. |
| Least Privilege | Providing users only the access necessary for their responsibilities. |
| Access Management | Establishing a foundation for controlling access to organizational resources. |
| Dynamic Membership | Automatically managing group membership using configured rules. |

---

## 5. Real-World Enterprise Applications

The tasks completed in this lab represent common responsibilities performed by IAM administrators and IT support professionals.

Examples include:

- Creating accounts for newly hired employees.
- Managing employee identity information.
- Organizing users into departmental security groups.
- Updating group membership when employees change departments.
- Maintaining centralized identity records.
- Preparing security groups for application and resource access assignments.

**Connection to IAM Roles:**

These responsibilities are directly related to entry-level IAM Analyst, Identity Administrator, Access Management Analyst, and Cloud Security Analyst positions.

---

## 6. Skills Demonstrated

Through this lab, I gained hands-on experience with:

- Microsoft Entra ID administration.
- Cloud-based identity management.
- User account creation and management.
- Security group administration.
- Group membership configuration.
- Identity directory organization.
- Assigned and dynamic group membership concepts.
- Foundational access management principles.
- Enterprise IAM administration workflows.

---

## 7. Lab Completion Summary

**Lab A successfully established the identity management foundation for the Chambers Corporation cloud environment.**

The following tasks were completed:

- [x] Created Microsoft Entra ID tenant.
- [x] Created 12 fictional employee accounts.
- [x] Reviewed individual user profiles.
- [x] Created security groups.
- [x] Assigned users to appropriate security groups.
- [x] Reviewed group configurations.
- [x] Captured screenshots documenting implementation.

**Outcome:**

A centralized identity directory was established with fictional employee accounts and organized security groups.

This environment provides the foundation for subsequent IAM security configurations, including authentication, Multi-Factor Authentication (MFA), Conditional Access, and Azure Role-Based Access Control (RBAC).

---

## 8. Next Steps

The next phase of this project builds upon the identity directory established in Lab A.

Future configurations include:

- Implementing Multi-Factor Authentication (MFA).
- Configuring Conditional Access policies.
- Reviewing authentication logs.
- Understanding authentication requirements.
- Implementing Azure RBAC.
- Applying least privilege to cloud resources.
- Exploring identity security monitoring.

**Lab A provides the foundation for understanding how organizations create, organize, and manage identities within a cloud environment.**
### Lab B — Multi-Factor Authentication & Conditional Access

Project Overview

This lab explores authentication security and identity protection using Microsoft Entra ID.

The objective was to configure and investigate Multi-Factor Authentication (MFA), register Microsoft Authenticator, test number matching, and review sign-in logs to understand how organizations protect employee accounts.

The lab uses a fictional organization, Chambers Corporation, and a dedicated test account.

**B1 — Security Defaults**

**Objective**

Enable Microsoft's built-in identity security protections.

**Activities**

- Accessed Microsoft Entra tenant properties.

- Located Security Defaults.

- Enabled Security Defaults.

Reviewed the purpose of built-in security protections.

**Real-World Application**

Security Defaults provide a baseline level of identity protection by helping organizations enforce stronger authentication requirements.

**Status**

Completed.

**B2 — Authentication Methods**

**Objective**

Understand and review the authentication methods available to organizational users.

**Activities**

- Reviewed Microsoft Entra authentication methods.

- Located Microsoft Authenticator configuration.

- Reviewed authentication method availability.

Investigated how users register authentication methods.

**Real-World Application**

IAM administrators manage authentication methods to ensure employees use approved and secure ways to verify their identities.

**Status**

Reviewed and documented.

**B3 — Microsoft Authenticator Registration**

**Objective**

Register Microsoft Authenticator for a dedicated test account.

**Test Account

Bob.Dale.Test

**Activities**

- Opened the test account's authentication registration process.

- Registered Microsoft Authenticator.

- Connected the account to the Authenticator application on an iPhone.

- Verified the registered authentication method.

**Real-World Application**

Organizations use authenticator applications to provide an additional layer of protection beyond passwords.

**Status**

Completed.

**B4 — Number Matching**

**Objective**

Test number matching as an additional authentication security measure.

**Activities**

- Initiated a sign-in using Bob.Dale.Test.

- Received a number-matching authentication challenge.

- Opened Microsoft Authenticator.

- Entered the displayed number, 74.

- Successfully approved the authentication request.

**Real-World Application**

Number matching helps reduce accidental authentication approvals and MFA fatigue attacks.

**Status**

Completed.

**B5 — Sign-in Logs and Authentication Details**

**Objective**

Investigate authentication activity using Microsoft Entra sign-in logs.

**Activities**

- Opened the Microsoft Entra sign-in logs.

- Located authentication events for Bob.Dale.Test.

- Reviewed successful sign-in results.

- Inspected Authentication Details.

- Investigated authentication status and previously satisfied requirements.

**Observations**

The reviewed event displayed:

- Succeeded: True

- Previously satisfied: True

- First factor requirement

A successful sign-in confirms that authentication succeeded, but a previously satisfied requirement does not independently establish that a new MFA challenge occurred during that particular event.

**Real-World Application**

Security and IAM analysts use sign-in logs to investigate authentication failures, suspicious sign-ins, and potential account compromise.
**
Status**

Completed — log review performed.

**B6 — Fresh MFA Verification**

**Objective**

Verify that MFA is enforced during a fresh authentication session.

**Testing Procedure**

1. Open a private browser session.

2. Sign in using the dedicated test account.

3. Complete the initial authentication step.

4. Check whether an MFA challenge is presented.

5. Complete the Authenticator verification.

6. Review the corresponding sign-in event.

7. Inspect Authentication Details to confirm the MFA result.

**Expected Evidence**

A fresh sign-in event showing successful MFA authentication.

**Status**

Pending final fresh sign-in verification.

**Conditional Access — Additional Learning
**
Conditional Access allows organizations to create policies that evaluate sign-in conditions before granting access.

Examples include:

- Requiring MFA for specific applications.

- Blocking access from specified locations.

- Requiring compliant devices.

- Applying additional authentication requirements based on risk.

Custom Conditional Access policies generally require Microsoft Entra ID P1 or an eligible licensing arrangement.

This lab used Security Defaults rather than custom Conditional Access policies because the available tenant did not have the required subscription.

Security Defaults and Conditional Access are different security approaches and should not be represented as the same configuration.

**Technologies and Concepts**

- Microsoft Entra ID

- Multi-Factor Authentication

- Microsoft Authenticator

- Number Matching

- Security Defaults

- Conditional Access

- Authentication Methods

- Sign-in Logs

- Authentication Details

- Identity Protection

 **Skills Demonstrated**

- Authentication method administration

- MFA registration and testing

- Number-matching verification

- Authentication troubleshooting

- Sign-in log investigation

- Identity security configuration

- Understanding Conditional Access

**Project Limitations**

Custom Conditional Access policies were not deployed because the tenant did not have the required licensing.

Fresh MFA verification remains a final evidence item until confirmed through a new sign-in event.

**Conclusion**

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
