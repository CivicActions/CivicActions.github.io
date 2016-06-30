---
title: Security Awareness and Tools
---

# Security Awareness and Tools

This is an appendix to the [CivicActions Security Policy](/Security/Policy) containing details that can and should be updated regularly as new technologies or patterns of use develop, with a goal of providing team members the best tools with which to maintain the security of company confidential and personal information.

_This is currently - and probably always will be - a work in progress. Pull Requests welcome._

## Password Management Tools

### Use a Password Manager
A password manager will enable you to have unique, strong passwords for every service that you log into. Good password managers will generate new passwords for you, auto-fill web forms, allow extra protection for high-security accounts (like banking), and more. Choose a password manager that encrypts locally (in your browser, so you don’t have to trust the provider to keep their data safe) and that has iPhone and Android apps that will auto-sync with the manager. At CivicActions, we currently recommend LastPass as it is the most full-featured, but we are keeping a close eye on the FOSS KeePass and Password Safe solutions.

### LastPass
- The [LastPass](https://lastpass.com/) password generator can easily create and maintain hundreds of different 16 character (or more!) passwords. And LastPass has free iPhone and Android apps.
- LastPass is used by the CivicActions System Admins and Infrastructure Support Team.
- We recommend LastPass premium but do not require it. A premium account will enable unlimited sync across your devices and more robust two-factor authentication.

## Use Two (Multi-) Factor Authentication (TFA, 2FA or MFA)
As your password manager grows to have more passwords in it - not only CivicActions’ systems and clients but also your personal bank accounts, credit cards, school records, etc. - it becomes increasingly important to have it protected by more than just a password. Two factor authentication includes something you know (your password) and something you have (e.g. your smartphone or perhaps a Yubikey) and can greatly increase the security of your systems. CivicActions recommends you use Two Factor Authentication for services that support it.

### Two-Factor Authenticators
There are many hardware and software tools for creating secure “one time passwords” (OTP). Two that we use internally are described below.

- Google Authenticator ...
- YubiKey ...

Partial list of services and links to related TFA documentation

- LastPass: [Multifactor Authentication Options](https://helpdesk.lastpass.com/multifactor-authentication-options/)
- Google: [2 Step Verification](https://support.google.com/accounts/topic/28786?hl=en&ref_topic=3382253)
- GitHub (especially for your [CivicAction account](https://github.com/CivicActions)): [Securing your account with two-factor authentication (2FA)](https://help.github.com/articles/securing-your-account-with-two-factor-authentication-2fa/)
- GitLab: See [your profile](https://git.civicactions.net/profile/account)
- Slack: [Enabling two-factor authentication](https://get.slack.help/hc/en-us/articles/204509068-Enabling-two-factor-authentication#enablingtwofactor-authentication)

### Setting up TFA for access to CivicActions Google Apps
CivicActions requires that its employees and contractors that are given access to the CivicActions Google Apps - that include GMail, Hangouts and Google Docs access - use Two Factor Authentication on their CivicActions Google Account.

_Actual steps tbd..._

## IT: Sharing Service Accounts

- If a service allows individual accounts, use only individual accounts and not shared credentials.
- Prefer services that allow individual accounts, services that allow TFA and secure password policies.
- If a service only allows a single account, have a shared LastPass master account that ideally only 2-3 trusted people have access to. From there share passwords out on an "as needed" basis only, including to individual day-to-day Lastpass accounts for the 2-3 trusted people.
- If the LastPass master account is a paid account it also allows sharing credentials in a way that makes the password harder for the person who you shared it with to recover/view/share (but still allow them to log in with it).
- Shared account passwords should rotate to ensure that only those users needing access continue to have access, revoking individual accounts especially when people leave.

## Phishing and Social Engineering

## Backups

## Secure Delete Files and Wiping Disks
