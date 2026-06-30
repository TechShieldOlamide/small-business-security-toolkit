# Credential Sharing Protocol for Remote Staff and Virtual Assistants

**Version:** 1.0  
**Last Updated:** June 2026  
**Built by:** TrustGrid Technology Limited  

---

## The Problem This Solves

Small businesses often work with remote staff, virtual assistants, or offshore contractors who need access to certain accounts but should never see the actual passwords. This protocol explains how to do that securely without ever sending a password in plain text.

---

## The Core Principle

Access should be given at the item level, not the vault level. A remote assistant should be able to log into specific tools they need for their job, without being able to see the password itself or access tools outside their role.

---

## Step by Step Setup

### Step 1 — Create a Role-Specific Vault or Collection

In your password manager, create a separate vault or collection containing only the credentials relevant to the assistant's role. For example, a social media VA gets access to social media accounts only, not banking or payroll.

### Step 2 — Enable View-Only or Use-Only Access

Most password managers allow you to grant access where the user can use the credential (autofill on login) without ever seeing the actual password in plain text. Enable this setting wherever possible.

### Step 3 — Set Up Individual Logins

Never give a shared login to a password manager account. Each person, including remote staff, should have their own login so all activity can be tracked individually.

### Step 4 — Enable 2FA on the Assistant's Account

Require two-factor authentication on the password manager account itself, not just the underlying services.

### Step 5 — Time-Limit Access Where Possible

If the engagement has a defined end date or the assistant only needs access temporarily, set a calendar reminder to review and revoke access at that point.

### Step 6 — Never Use These Methods

- [ ] Sending passwords via email
- [ ] Sending passwords via WhatsApp, Slack, or any chat platform
- [ ] Sharing a master password to the entire vault
- [ ] Writing passwords in a shared document
- [ ] Verbally sharing passwords over a call without follow-up access review

---

## What to Do When the Engagement Ends

1. Revoke the assistant's access immediately in the password manager
2. Change any passwords the assistant had direct knowledge of (not just managed access to)
3. Review login activity for the affected accounts in the days following offboarding
4. Document the offboarding date and action taken

---

## Quick Reference: Access Levels

| Access Level | What It Means | When to Use |
|---|---|---|
| Full Vault Access | Sees and can edit all credentials | Owner, senior admin only |
| Collection Access | Sees only credentials in their assigned collection | Department heads, team leads |
| Use-Only Access | Can log in via autofill but never sees the password | Remote staff, VAs, contractors |
| No Access | Cannot see or use any credentials | Anyone not requiring system access |

---

## Credential Sharing Log Template

| Date Granted | Person | System/Account | Access Level | Reason | Date Revoked |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*
