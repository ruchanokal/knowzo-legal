---
layout: default
title: Account Deletion
---

# Account Deletion — Knowzo

**App:** Knowzo
**Developer:** Ruchan Okal
**Contact:** knowzo@yandex.com

This page explains how to delete your Knowzo account and the data associated with it. It exists to meet the Google Play and App Store requirements for account-deletion transparency for apps that support account creation.

## 1. In-App Deletion (recommended)

The fastest way to delete your account is from inside the app:

1. Open Knowzo.
2. Go to the **Profile** tab → tap the gear icon (top right) to open **Settings**.
3. Scroll to the **Account** section.
4. Tap **"Delete my account"**.
5. Confirm in the dialog that appears.

Deletion is immediate. After confirming, you are signed out and returned to the welcome screen. There is nothing else you need to do.

## 2. Deletion By Email Request

If you can no longer open the app (for example, you've already uninstalled it), email **knowzo@yandex.com** from the email address linked to your Knowzo account with the subject "Delete my Knowzo account". Include the display name you used in the app if you know it.

Requests are processed within 30 days. We will confirm completion by reply email.

## 3. What Is Deleted

When your account is deleted, the following are permanently removed from our systems:

- Firebase Authentication record (UID, email if you upgraded to a permanent account, password hash)
- Your profile document: display name, country, language preference
- Your gameplay data: total points, lifetime accuracy, current streak, daily-quest progress, lifetime games played
- Your entries on the global, country, and weekly leaderboards
- Recent session records (the per-round answer ledger)

## 4. What Is Retained, And For How Long

A small amount of data is retained for limited periods after deletion:

- **Cloud Functions request logs** (Google-managed): up to 30 days, then automatically purged. These logs do not contain your display name, email, or password — they contain anonymous request metadata used by Google for service reliability.
- **Aggregated, anonymized analytics counters** (for example, "total questions answered today across all users"): retained indefinitely because they cannot be linked back to you.
- **Crash reports submitted before deletion**: retained up to 90 days by Firebase Crashlytics, then automatically purged.

No data that can identify you is retained beyond the windows listed above.

## 5. Partial Data Deletion

We do not currently offer partial data deletion as a separate flow. The account-deletion action above removes all your data in one step. If you want only certain fields cleared (for example, change your display name without deleting your account), you can do that from the Settings screen in the app.

## 6. Questions

For any question about this process, write to **knowzo@yandex.com**. This page may be updated; the current version is always at <https://ruchanokal.github.io/knowzo-legal/account-deletion/>.

---

*Last updated: May 2026*
