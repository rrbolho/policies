---
title: Homyk Privacy Policy
---

# Privacy Policy for Homyk

**Last updated:** August 18, 2026

Homyk ("the app", "we", "us") is a **local-first** home management and
maintenance history app. This policy explains what information the app
handles, why, and the choices you have.

## Overview

Homyk is designed to work with **no traditional backend server**. All the
data you enter — houses, rooms, devices, photos, invoices, and maintenance
records — is stored **locally on your device**. We do not operate any
server that receives or stores your data. The only optional exception is
cloud backup, described below, which is stored directly in **your own**
Google Drive or iCloud account, not on infrastructure we control.

## Information We Collect

### 1. Data you provide inside the app

When you use Homyk, you may enter information such as:

- Houses, rooms, and devices (names, categories, brands, models, serial
  numbers, purchase dates, warranty dates, notes)
- Photos and documents you attach (device photos, purchase invoices,
  maintenance service invoices)
- Maintenance records and scheduled appointments

This data is stored in a local database on your device (SQLite) and is
**never transmitted to us**. We have no access to it unless you explicitly
choose to back it up to the cloud (see below).

### 2. Cloud backup data (optional)

If you turn on cloud backup or press "Back Up Now" in Settings:

- **Android:** the app signs you in with your Google account and uploads a
  backup file to a **hidden, app-private folder** in your own Google Drive
  (Google's `appDataFolder`, using the `drive.appdata` scope). This folder
  is not visible in your normal Drive file list and is not accessible to
  any other app. We do not have access to this file — it lives entirely in
  your Google account.
- **iOS:** iCloud backup is planned but not yet available in the app.
- If enabled, the app may also perform this backup automatically, roughly
  once a day, but **only** if you are already signed in — it never asks you
  to sign in on its own in the background.
- The backup includes the data described above, plus your locally stored
  photos/documents (embedded in the backup file so they can be restored).

You can stop cloud backup at any time by revoking Homyk's access from your
Google Account's [third-party access settings](https://myaccount.google.com/permissions),
and you can delete a previously uploaded backup from Google Drive's
["Manage third-party apps"](https://drive.google.com/settings) storage
view.

### 3. Advertising data (Android, free tier only)

On Android, while you are on the free tier, Homyk shows banner ads
through **Google AdMob**. iOS never shows ads, on any tier.

To serve ads, Google's AdMob SDK may collect device identifiers (such as
the advertising ID) and other technical/usage data, in accordance with
[Google's Privacy Policy](https://policies.google.com/privacy) and
[How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites).
You can opt out of personalized advertising at any time in your device's
ad settings.

Upgrading to Premium removes all ads.

### 4. Purchase data

Premium is a one-time purchase processed through **Google Play Billing**.
We do not see or store your payment details — that's handled entirely by
Google Play. To manage entitlements, the app uses **RevenueCat**, a
third-party subscription/purchase management service, which receives an
anonymous app-user identifier and purchase receipt data from the store.
See [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy) for
details.

## Data Storage and Retention

- Data you enter stays on your device until you delete it or uninstall the
  app.
- Backup data (if you opt in) stays in your own Google Drive/iCloud account
  until you delete it or revoke access, independent of whether Homyk is
  still installed.
- Restoring from a backup replaces all local data on the device with the
  backup's contents.

## Third-Party Services

Homyk uses the following third-party services, each governed by its own
privacy policy:

| Service | Purpose | Platform |
|---|---|---|
| Google AdMob | Displaying ads on the free tier | Android only |
| Google Drive / Google Sign-In | Optional cloud backup | Android only |
| RevenueCat | Managing Premium purchase entitlement | Android (iOS planned) |
| Google Play Billing | Processing the Premium purchase | Android |

We do not sell your information to third parties, and we do not use your
data for any purpose beyond providing the app's own functionality.

## Your Rights and Choices

- **Access/delete your data:** since your data lives on your device, you
  can view, edit, or delete it at any time directly in the app.
- **Cloud backup:** entirely optional. You can disable it, delete an
  existing backup, or revoke Homyk's Google account access at any time
  (links above).
- **Ads:** you can opt out of personalized ads via your device settings,
  or remove ads entirely by upgrading to Premium.
- **Uninstalling the app** deletes all locally stored data (any cloud
  backup you created remains in your own account until you delete it
  separately).

## Children's Privacy

Homyk is not directed at children under the age of 13 (or the applicable
age of digital consent in your jurisdiction), and we do not knowingly
collect personal information from children.

## Data Security

Your data is stored locally on your device using standard OS-level app
sandboxing. Optional cloud backups are transmitted over encrypted
connections (HTTPS) to your own Google Drive/iCloud account, protected by
your own account credentials.

## Changes to This Policy

We may update this policy from time to time. Changes will be posted on
this page with an updated "Last updated" date.

## Contact Us

If you have questions about this privacy policy, contact us at:

**rrbolho+homykapp@gmail.com**
