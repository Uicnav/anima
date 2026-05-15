---
layout: default
title: Privacy Policy
permalink: /privacy/
---


**Last updated:** 2026-05-09
**Effective:** 2026-05-09

## 1. Who we are

This policy describes how Anima ("Anima", "the app", "we", "us", "our")
collects, uses, and protects your personal data.

The app is operated by **Ion Varanita**, a sole developer based in
Romania. You can contact the data controller at:

- Email: **ion.varanita18@gmail.com**
- Country of operation: Romania

For postal correspondence, write to the email address above and we
will provide a current postal address on request — this avoids
publishing a personal home address while still satisfying GDPR Art. 13
controller-contact requirements.

When this policy says "we", it refers to the data controller above.

## 2. What this policy covers

This policy applies to your use of:

- The Anima mobile app on iOS and Android
- Any of our services that link back to this policy

It does NOT cover websites, apps, or services operated by third
parties — those have their own privacy policies, listed in
[Section 6](#6-third-party-processors).

## 3. What data we collect

### 3.1 Data you give us directly

| Type | When | Why |
| --- | --- | --- |
| Email address | Sign-up, sign-in | Account creation, authentication, security alerts |
| Username (unique handle) | Profile setup | Identify you in the community without exposing your real name |
| First and last name | Profile setup | Personalise your profile and chats with matches |
| Display name (legacy users) | Profile setup | Same as above; superseded by first / last name on new accounts |
| Profile photo (optional) | Profile setup | Same as above |
| Short bio (optional) | Profile setup | Same as above |
| Wishlist categories | Profile setup | Match you with relevant items |
| Item photos | Listing items for trade | Show your items in the discovery feed |
| Item descriptions, categories, condition | Listing items | Same as above |
| Chat messages | Messaging a match | Deliver messages to the other person |
| Location (precise or approximate) | When you grant permission | Show items near you, score match relevance |

### 3.2 Data collected automatically

| Type | Source | Why |
| --- | --- | --- |
| Device push notification token | Firebase Cloud Messaging | Deliver match and message notifications |
| App version, OS version, device model | App start-up | Diagnose crashes, target compatibility fixes |
| Crash reports and error logs | Sentry SDK | Find and fix bugs |
| Authentication tokens, session IDs | Supabase Auth | Keep you signed in across app restarts |

We do NOT collect:

- Your contacts list
- Your health, biometric, or financial data
- Your microphone or call data
- IDFA / advertising identifiers (App Tracking Transparency disabled
  by design — `NSPrivacyTracking = false` in our iOS privacy manifest)

### 3.3 Information from third-party sign-in

If you sign in with Google or Apple, we receive the email address and
the basic profile information they provide. We do not receive your
contacts, calendar, or any other Google/Apple account data.

## 4. Why we use your data

Your data is processed for the following purposes:

| Purpose | Legal basis (GDPR Art. 6) |
| --- | --- |
| Create and maintain your account | Contract (Art. 6(1)(b)) |
| Match you with other users for trades | Contract |
| Show items near you | Consent (Art. 6(1)(a)) — you opt in to location |
| Send transactional notifications (match made, new message) | Contract |
| Send security alerts (e.g. unusual login) | Legitimate interest (Art. 6(1)(f)) |
| Diagnose crashes and improve app stability | Legitimate interest |
| Detect and prevent fraud or abuse | Legitimate interest |
| Comply with legal obligations | Legal obligation (Art. 6(1)(c)) |

We do NOT use your data for behavioral advertising, profiling, or
sale to third parties.

## 5. Who can see your data

### 5.1 Other community members

When you list an item, other Anima users can see:

- Your first name, last name, and `@username`
- Your profile photo (if you set one)
- Your item photos, descriptions, and category
- Your approximate distance from them (not your exact address)

When you match with someone, both of you see each other's full
profile and listed items, and you can chat directly.

### 5.2 Our service providers

We share data only with the third-party processors required to
deliver the service. Each is bound by data processing agreements
where applicable.

## 6. Third-party processors

| Provider | Purpose | Data shared | Where |
| --- | --- | --- | --- |
| **Supabase Inc.** (USA) | Database, authentication, file storage | Account, profile, items, photos, chat | EU and US data centers depending on region |
| **Google Firebase** (USA) | Push notifications via FCM | Push token, device info | Global Google infrastructure |
| **Apple Push Notification Service** | Push notifications on iOS | Push token | Apple infrastructure |
| **Sentry GmbH** (Germany / USA) | Crash reporting | Crash logs, device info, redacted user ID | EU and US |
| **Google LLC** | OAuth Sign-In with Google | Email, basic profile (only if you choose Google sign-in) | USA |
| **Apple Inc.** | Sign in with Apple | Email (relayed), basic profile (only if you choose Apple sign-in) | USA |

International transfers to the United States rely on Standard
Contractual Clauses (SCCs) and the EU–U.S. Data Privacy Framework
where applicable.

## 7. How long we keep your data

| Data | Retention |
| --- | --- |
| Account, profile, items, chat | While your account is active |
| Account data after deletion | Up to 30 days, then permanently erased (some legal-compliance copies may be retained longer if law requires) |
| Crash reports | Up to 90 days |
| Push tokens | Up to 12 months of inactivity, then revoked |
| Authentication tokens | Up to 30 days, then refreshed |

You can delete your account at any time from the in-app profile
screen. After deletion, your public listings, profile, and chat
content are removed within 30 days.

## 8. Your rights

If you are in the European Economic Area, the United Kingdom, or
Switzerland, you have the following rights under GDPR:

- **Access** — get a copy of the personal data we hold about you.
- **Rectification** — fix inaccurate or incomplete data.
- **Erasure** — ask us to delete your data ("right to be forgotten").
- **Restriction** — ask us to limit processing.
- **Portability** — receive a machine-readable export.
- **Objection** — object to processing based on legitimate interest.
- **Withdraw consent** — for any processing based on consent.
- **Lodge a complaint** with your local supervisory authority. In
  Romania, this is the **National Supervisory Authority for Personal
  Data Processing (ANSPDCP)** — https://www.dataprotection.ro/.

To exercise any right, email **ion.varanita18@gmail.com**. We respond
within 30 days.

If you are in California, you have similar rights under the CCPA
(right to know, delete, correct, and opt out of sale — we do not sell
your data).

## 9. Security

We protect your data with:

- Encrypted transport (HTTPS/TLS) for all network traffic
- Encrypted storage at rest in Supabase
- Hashed passwords (we never store plaintext passwords)
- Row-level security policies that restrict who can read your data
- Bug-bounty-friendly disclosure: report vulnerabilities to
  ion.varanita18@gmail.com.

No system is perfectly secure. If a breach affects you, we will
notify you within 72 hours as required by GDPR Art. 33–34.

## 10. Children

Anima is not directed at children under 16 (or the equivalent age
under your local law). We do not knowingly collect personal data from
children. If you are a parent or guardian and believe we hold a
child's data, contact us and we will remove it.

## 11. Changes to this policy

We may update this policy as the app evolves. Material changes are
announced in the app and via email at least 7 days before they take
effect. Continued use of the app after a change means you accept the
new policy.

The "Last updated" date at the top of this document indicates the
current version.

## 12. Contact

Questions about this policy or your data:

**Email:** ion.varanita18@gmail.com
**Subject:** "Privacy: <your question>"

---

*This is version 1.0 of the Anima privacy policy. Earlier versions
are available on request.*
