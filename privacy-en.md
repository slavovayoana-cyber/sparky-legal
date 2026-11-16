# Privacy Policy

🇬🇧 **English** · [🇧🇬 Български](./privacy-bg) · [🇪🇸 Español](./privacy-es) · [🇩🇪 Deutsch](./privacy-de) · [🇫🇷 Français](./privacy-fr) · [🇮🇹 Italiano](./privacy-it) · [🇵🇹 Português](./privacy-pt)

**Last updated: November 16, 2026**
**Effective: November 16, 2026**

This Privacy Policy describes how the Sparky Kids application ("Sparky", "the App", "we", "us") handles information when you and your child use it, on both iOS and Android. We've designed Sparky to keep your family's day-to-day data on your own device.

---

## TL;DR

- All information your child or you enter (names, tasks, stars, streaks, rewards, etc.) is stored **only on your device** and never leaves it.
- We collect **anonymous, non-personal usage analytics** (e.g. "a task was completed") only if a parent opts in — to understand how the App is used and improve it. No names, no advertising identifiers, no personal data.
- Sparky Premium is an **optional** subscription or one-time purchase, billed entirely by the **Apple App Store** or **Google Play** — we never see or store your payment details.
- We have **no advertisers** and do **not** collect or use any advertising identifier (IDFA/GAID). The App requires no account or login.
- Analytics data is processed by PostHog on EU servers; purchase status is processed by RevenueCat. Neither is sold or used for advertising.

---

## 1. Who We Are

Sparky Kids is developed by an independent developer (Noomup).
**Contact:** sparkykidsapp@gmail.com

---

## 2. Information We Do Not Collect

We do not collect, request, or have access to any of the following:

- Names, email addresses, phone numbers, or any contact information
- IP addresses, advertising identifiers (IDFA/GAID), or any identifier that could be linked to a specific person
- Geographic or precise location data
- Photos, contacts, microphone audio, or any other on-device content outside the App
- Health, fitness, financial, or biometric data
- Payment card numbers or billing details — these are handled entirely by Apple or Google, never by us
- Browsing history, search history, or the content of your child's tasks, names, or rewards
- Any data about your child's identity

We do not use advertising, attribution, or third-party tracking services.

---

## 3. Information Stored Locally on Your Device

For Sparky to work as a habit-and-reward app, the following information is stored on your device using the operating system's local app storage (AsyncStorage). **None of this data ever leaves the device as part of normal app storage.** It is not synced to a cloud, not backed up to our servers (because we have no servers), and not shared with any third party.

- The child's display name (entered by the parent during onboarding)
- The child's age group (selected by the parent during onboarding)
- The chosen mascot character, and an optional custom photo avatar the parent picks from the device's own photo library (Premium feature — never uploaded anywhere)
- The parent PIN (used only to lock the parent zone on the same device)
- Daily tasks, bonus activities, and milestones (the rewards your family configures)
- Star totals, streak counts, task completion timestamps, and freeze usage
- App preferences (language, sound, haptics, animations, analytics opt-in choice)
- Up to 30 days of history snapshots (for the parent panel's "past days" view)
- The list of child profiles in your family (up to 3)
- Whether Sparky Premium is currently active (checked against Apple/Google, see §4)

When you delete the App from your device, or use the in-app "Reset progress" action in the parent settings, all of this information is permanently erased.

---

## 4. Sparky Premium — Subscriptions & Purchases

Sparky Premium is entirely **optional** and unlocks extra features (more child profiles, unlimited tasks, task packs, custom avatars, extended history, printable certificates). It is offered as a monthly subscription, an annual subscription, or a one-time lifetime purchase.

- **Billing** is handled entirely by the **Apple App Store** (iOS) or **Google Play** (Android). We never see, receive, or store your card number or any payment details — that happens between you and Apple/Google directly.
- We use **RevenueCat** (revenuecat.com) to validate purchases and keep track of whether your subscription is active across app sessions. RevenueCat receives a randomly generated anonymous app user ID and your purchase/subscription status (which product, renewal date) — never your name, email, or payment information.
- Subscriptions **auto-renew** until cancelled. You can cancel or manage your subscription at any time from your Apple ID or Google Play account settings — we cannot cancel it for you from our side.
- Because Sparky is used by children, a neutral verification question (e.g. a simple sum) is shown before the purchase screen itself, so a child cannot reach it without a parent present.

RevenueCat's own privacy practices are described at revenuecat.com/privacy.

---

## 5. Notifications

Sparky uses your device's local notification system (iOS or Android) to send friendly reminders:

- A daily reminder to check today's tasks (you control the time and whether it's on)
- A "save your streak" nudge in the evening (only when there's a streak to protect and today's tasks aren't done yet)
- A one-time "come back tomorrow" nudge the day after your child's very first completed task
- A "task complete" sound when a focus timer reaches zero

These notifications are scheduled and delivered entirely by your device's operating system. **We do not see them, we do not control their delivery from our side, and they contain no information that is sent anywhere.**

You can disable all notifications at any time:
- iOS: Settings → Notifications → Sparky Kids → toggle off
- Android: Settings → Apps → Sparky Kids → Notifications → toggle off
- Or inside the App: Parent Zone → Settings → Notifications

---

## 6. Children's Privacy

Sparky is designed primarily for children aged 4 to 12. We take children's privacy very seriously.

- We do **not** knowingly collect any personal information from children (or anyone else).
- We do **not** require a child to enter any information; the parent sets up the child's display name and age group during onboarding.
- No data your family enters ever leaves your device as part of normal app storage — see §3.
- The App contains no third-party advertising, no external links visible to the child, and no public communication features.
- The parent zone is PIN-protected, and any purchase screen additionally requires a neutral parent-verification question (§4), so children cannot change settings, make a purchase, or expose data inadvertently.

We comply with applicable children's privacy laws including the U.S. Children's Online Privacy Protection Act (COPPA) and the EU General Data Protection Regulation (GDPR), including its protections for children (GDPR-K).

If you are a parent or guardian and believe that we have somehow obtained personal information from your child, please contact us at sparkykidsapp@gmail.com and we will address your concern promptly.

---

## 7. Third-Party Services

Sparky is built on the React Native and Expo open-source frameworks, and uses the standard platform frameworks for notifications and local storage on iOS and Android. None of these frameworks transmit your data to us or to any third party as part of how we use them in the App.

### Purchases — RevenueCat

See §4 above.

### Analytics — PostHog

If — and only if — a parent explicitly opts in on the onboarding screen, we use **PostHog** (posthog.com) to collect anonymous usage analytics. You can change this choice at any time in Parent Zone → Settings → Privacy. Nothing is collected before you opt in, and opting out later stops all future collection immediately.

**What is sent to PostHog (only if you opted in):**
- Anonymous in-app events such as: app opened, task completed, timer started/completed/cancelled, reward redeemed, onboarding step viewed, premium paywall viewed/purchase events
- App version, platform (iOS/Android), and general device OS info (e.g. "iOS 18") — not your device's advertising identifier
- A randomly generated anonymous identifier that stays the same across app sessions so we can measure things like "how many people open the app again the next day" — it is not linked to your name, email, or any other personal identity
- Whether Sparky Premium is active (as a true/false flag only)

**What is NOT sent to PostHog:**
- Your child's name, age, or any entered content
- Task titles, reward names, or any text you have typed
- Payment details, card numbers, or anything from the App Store/Google Play purchase flow itself
- Your advertising identifier (IDFA/GAID) — we do not collect or use this, ever
- Precise location data

PostHog data is processed on servers located in the **European Union** and is governed by PostHog's privacy policy (posthog.com/privacy). We do not sell this data, use it for advertising, or share it with any party other than PostHog for the purpose of providing the analytics service.

We do not embed advertising SDKs, attribution SDKs, or any other telemetry framework.

---

## 8. Data Security

Because Sparky does not transmit your day-to-day data anywhere, the security of that data depends on the security of your device. We recommend:

- Keeping your device updated with the latest security patches
- Using a strong device passcode and Face ID / Touch ID / fingerprint unlock
- Setting a non-trivial parent PIN inside the App (avoid "0000" or "1234")

---

## 9. Your Rights & How to Request Deletion

Because Sparky does not store your family's day-to-day data on any server, there is no copy on our side to access, correct, or export — it all lives on your device under your full control.

**To delete everything Sparky has stored on your device:**
- Use the "Reset progress" button in the parent settings (Parent Zone → Settings → Reset), or
- Uninstall the App from your device.

Both actions permanently erase all Sparky data from your device, with no copy anywhere else.

**To request deletion of analytics data** (only applicable if you had opted in to analytics), email us at sparkykidsapp@gmail.com with your approximate opt-in date and platform (iOS/Android), and we will have it removed from PostHog on your behalf.

**To cancel a Sparky Premium subscription** or request a refund, this must be done through your Apple ID (Settings → [your name] → Subscriptions) or Google Play (Play Store app → Payments & subscriptions) account settings — we have no ability to process this on our side, since billing happens directly between you and Apple/Google.

---

## 10. Changes to This Policy

We may update this Privacy Policy as Sparky evolves. When we do, we will update the "Last updated" date at the top of this page and, for material changes, include a notice in the App's "What's New" release notes.

---

## 11. Contact Us

If you have any questions about this Privacy Policy or about Sparky's privacy practices, please email us at:

**sparkykidsapp@gmail.com**

We respond to all parent inquiries personally.
