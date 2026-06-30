# Two-Factor Authentication (2FA) Rollout Checklist

**Version:** 1.0  
**Last Updated:** June 2026  
**Built by:** TrustGrid Technology Limited  

---

## What is 2FA and Why It Matters

Two-factor authentication adds a second step to logging in beyond just a password. Even if someone steals or guesses a password, they cannot get into the account without also having the second factor, usually a code from an app on your phone.

For a small business, enabling 2FA on a handful of critical accounts is one of the highest impact, lowest cost security improvements you can make.

---

## Priority Order for Rollout

### Phase 1 — Critical Accounts (Do This First)

- [ ] Business email (the account that can reset passwords for everything else)
- [ ] Banking and payment platforms
- [ ] Payroll system
- [ ] Password manager itself
- [ ] Domain registrar (where your website domain is managed)
- [ ] Cloud storage (Google Drive, Dropbox, etc.)

### Phase 2 — Business Software

- [ ] CRM system
- [ ] Accounting software
- [ ] Social media business accounts
- [ ] Project management tools
- [ ] Any software that stores customer data

### Phase 3 — Everything Else

- [ ] Any remaining business accounts with logins
- [ ] Personal accounts used for business purposes (recommend separating these)

---

## Choosing a 2FA Method

| Method | Security Level | Recommendation |
|---|---|---|
| Authenticator app (Google Authenticator, Authy, Microsoft Authenticator) | High | Recommended for most accounts |
| Hardware security key | Highest | Recommended for the most critical accounts (email, banking) if budget allows |
| SMS text message | Lower | Use only when no other option is available, vulnerable to SIM swapping |
| Email-based codes | Lower | Avoid if possible, especially if email itself is the account being protected |

---

## Setup Steps for Each Account

1. Log into the account's security settings
2. Locate the two-factor authentication or multi-factor authentication option
3. Choose authenticator app as the method where available
4. Scan the QR code with your chosen authenticator app
5. Save the backup codes provided in a secure location (your password manager, not a sticky note)
6. Test that the 2FA works by logging out and back in
7. Document which accounts have 2FA enabled

---

## Common Issues and Fixes

**Lost phone with authenticator app:**
Use the backup codes saved during setup, or contact the service's account recovery process. This is why saving backup codes is essential.

**Staff resistance to the extra login step:**
Explain that it adds about 5 seconds to login but prevents the kind of breach that could take down the business. Most resistance fades once people get used to the routine.

**SMS 2FA preferred for convenience:**
Acceptable as better than nothing, but recommend upgrading to an authenticator app for critical accounts as soon as practical.

---

## Rollout Tracker

| Account | 2FA Method | Date Enabled | Backup Codes Saved | Status |
|---|---|---|---|---|
| Business Email | | | Yes / No | |
| Banking | | | Yes / No | |
| Payroll | | | Yes / No | |
| Password Manager | | | Yes / No | |
| Domain Registrar | | | Yes / No | |
| CRM | | | Yes / No | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*
