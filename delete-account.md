---
layout: default
title: Delete your account
permalink: /delete-account/
---


**Last updated:** 2026-05-15

This page explains how to delete your **Anima** account and what
happens to your data afterwards. Anima is operated by **Ion Varanita**,
a sole developer based in Romania.

## 1. Delete your account from inside the app (recommended)

The fastest way to delete your account is from within Anima:

1. Open the **Anima** app on your phone.
2. Sign in if you are not already signed in.
3. Tap **Profile** in the bottom navigation.
4. Tap the **Settings** icon (top right).
5. Scroll to the bottom and tap **Delete account**.
6. Read the confirmation dialog and tap **Delete** to confirm.

Your account is then scheduled for deletion immediately. You will be
signed out and your profile will stop appearing in the discovery feed
right away.

## 2. Delete your account by email

If you have lost access to the app or to the email address used to
sign in, you can request deletion by email:

- **Send an email to:** [ion.varanita18@gmail.com](mailto:ion.varanita18@gmail.com)
- **Subject:** `Delete my Anima account`
- **Include:** the email address or `@username` associated with your
  account, so we can locate it.

We respond within **30 days** as required by GDPR Art. 12(3), and in
practice usually within a few business days.

## 3. What data is deleted

The following data is **deleted permanently** within 30 days of your
request:

- Your profile (first name, last name, username, bio, profile photo)
- Your account credentials and authentication tokens
- All items you listed (photos, descriptions, categories, condition)
- All chat messages you sent or received
- Your swipes (likes, passes) and matches
- Your wishlist categories
- Your location data
- Your push-notification device tokens
- Your blocks and your reports

This includes files stored in **Supabase Storage** (item photos and
profile avatars) — they are removed from the storage bucket as part
of the same deletion flow.

## 4. What data is kept, and why

A small amount of data may be retained beyond the 30-day window when
the law requires it:

| Data | How long | Why |
| --- | --- | --- |
| Soft-deletion record (your account ID + deletion timestamp) | Up to **30 days** after deletion | Lets us reverse an accidental deletion if you contact us in time, and prevents reuse of the username during that window |
| Abuse / fraud records (if your account was banned or reported) | Up to **24 months** | Legal obligation and protection of other users from repeat offenders |
| Crash reports containing a redacted user ID | Up to **90 days** | Diagnose bugs; cannot be re-linked to your account once the soft-deletion window closes |
| Tax or accounting records (does not apply to free accounts in v1.0) | As required by Romanian and EU law | Legal obligation under the EU Tax Directive |

After the retention periods above expire, the corresponding records
are permanently erased.

## 5. Cancelling a deletion

If you change your mind, email us at
[ion.varanita18@gmail.com](mailto:ion.varanita18@gmail.com) **within
30 days** of deletion and we will restore your account.

After 30 days, deletion is permanent and we are no longer able to
recover your account, profile, items, or chat history. You can of
course create a new account at any time.

## 6. Your other rights

Deleting your account is one of the rights guaranteed under the
GDPR. You also have the right to access, rectify, restrict, or port
your data without deleting your account. See the [Privacy
Policy](./privacy/) section 8 for the full list and how to exercise
them.

## 7. Contact

Questions about account deletion:

**Email:** [ion.varanita18@gmail.com](mailto:ion.varanita18@gmail.com)
**Subject:** `Delete my Anima account`
