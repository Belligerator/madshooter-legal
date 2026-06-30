# Mad Shooter — Privacy Policy

> **DRAFT — review before publishing.** This is the source for the public privacy-policy page
> (GitHub Pages). It doubles as the **account & data deletion request** page that Google Play
> requires (see § *Deleting your account and data*). Fill the `[...]` placeholders, then publish.
>
> Reflects what the app actually collects as of 2026-06-30 (Firebase Auth/Analytics/Crashlytics,
> own backend telemetry). Keep in sync with [ADR 0024](../adr/0024-firebase-auth-token-exchange.md),
> [ADR 0031](../adr/0031-firebase-analytics-separate-from-telemetry.md),
> [ADR 0033](../adr/0033-apple-sign-in-and-account-deletion.md) and the
> [Play Data Safety answers](play-data-safety-answers.md).

**Last updated:** 2026-06-30

This Privacy Policy explains how **Belligerator** ("we", "us") — an independent game developer
based in the Czech Republic — handles your data in the mobile game **Mad Shooter**
(package `cz.belli.madshooter`) on Android and iOS. Contact: **dmitrij.buckovsky@gmail.com**.
Belligerator is operated by a private individual; the developer's full legal name is available on request.

## Summary

- We create an account so you can save your progress and sync it across devices.
- We use Google Firebase (Authentication, Analytics, Crashlytics) and our own backend.
- We do **not** sell your data and do **not** share it with third parties for advertising.
- The game is intended for players **aged 13 and over** and is not directed to children.
- You can **delete your account and all associated data** at any time (see below).

## What we collect and why

| Data | Why | Legal basis (GDPR) |
|---|---|---|
| **Account identifiers** — Firebase user ID (UID), in-game Player ID | Create your account, save and sync progress | Contract (Art. 6(1)(b)) |
| **Email address** — when you sign in with Google or Apple | Link your account so you don't lose progress; we receive it via the sign-in provider and do **not** store it in our own database | Contract (Art. 6(1)(b)) |
| **Profile data** — nickname, chosen avatar | Display your pilot identity in-game | Contract |
| **Gameplay data / telemetry** — levels played, results, in-game economy events, tied to your Player ID | Run the game (progress, rewards), balance and improve levels | Contract; Legitimate interest (Art. 6(1)(f)) |
| **Analytics** — a pseudonymous app instance ID and usage events (Firebase Analytics), associated with your Firebase UID | Understand how the game is used and improve it | Consent / Legitimate interest (see § *Analytics & your choices*) |
| **Crash & performance data** — crash logs, device model, OS version (Firebase Crashlytics) | Diagnose crashes and keep the game stable | Legitimate interest |
| **Apple sign-in token** (iOS only) — an encrypted Apple refresh token, stored at rest (AES-256-GCM) | Required so we can revoke Apple access when you delete your account | Legal obligation / Contract |

We do **not** collect precise location, contacts, photos, microphone, or advertising identifiers.
The game currently contains **no ads**; if ads are added later, this policy will be updated and you
will be asked for consent where required.

## Who processes your data

- **Google (Firebase / Google Cloud)** — Authentication, Analytics, Crashlytics, and our backend
  hosting. Google acts as our processor. See Google's privacy policy.
- **Neon (database) / Google Cloud Run (backend)** — store and process your account and gameplay data.

These providers operate servers in the **EU and the United States**, so your data may be transferred
to the US. Such transfers rely on the appropriate safeguards (e.g. Standard Contractual Clauses).

We do **not** share your data with third parties for their own marketing.

## Analytics & your choices

Analytics and crash reporting are currently enabled by default and can be turned **off** in the game's
settings (a device-local opt-out). A full first-launch consent prompt will ship together with ads in a
future version. When disabled, the game stops sending analytics and crash data from your device.

## Data retention

We keep your account and gameplay data for as long as your account exists. When you delete your account,
the associated data is deleted as described below. Crash/analytics data is retained for a limited period
according to Firebase's default retention and then deleted or anonymised.

## Deleting your account and data

You can delete your account and all associated personal data:

- **In the app:** open **Profile → Delete account**. This permanently removes your account, your
  game progress, and (on iOS) revokes the linked Apple sign-in.
- **By request:** if you cannot use the in-app option, email **dmitrij.buckovsky@gmail.com** from the address linked
  to your account, or include your **Player ID** (shown in the app under Profile), and we will delete your
  data within 30 days.

Deletion removes your `players` record, your Firebase user, and any stored Apple token. Residual analytics
identifiers are purged according to Firebase retention settings.

## Your rights (EU/EEA — GDPR)

You have the right to access, correct, delete, restrict, or object to the processing of your data, and to
data portability. To exercise these rights, contact **dmitrij.buckovsky@gmail.com**. You also have the right to lodge
a complaint with your data protection authority (in the Czech Republic: Úřad pro ochranu osobních údajů, ÚOOÚ).

## Children

Mad Shooter is intended for players **aged 13 and over** and is **not** directed to children. We do not
knowingly collect data from children under 13. If you believe a child has provided us data, contact us and
we will delete it.

## Security

Data in transit is protected with HTTPS/TLS. The Apple sign-in token (iOS) is encrypted at rest.

## Changes

We may update this policy. Material changes will be reflected by a new "Last updated" date on this page.

## Contact

**Belligerator** (independent developer, Czech Republic) — **dmitrij.buckovsky@gmail.com**.
