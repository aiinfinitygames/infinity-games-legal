# Privacy Policy — WC Game

**Effective date:** 2026-05-27
**Publisher:** Infinity Games
**Contact:** ai.infinitygames@gmail.com

This is the privacy policy for the mobile application **WC Game** ("the App"), published by Infinity Games ("we", "us", "our"). This policy explains what data the App collects, how we use it, and which third parties receive it.

We do not require you to create an account, and we do not collect your name, email address, phone number, contacts, photos, or precise location.

---

## 1. Data we collect

### 1.1 Anonymous device identifier
The first time the App runs, it generates a random anonymous device ID (a string like `dev-a3f1b2c4d5e6f70123456789`). This ID is stored only on your device and is sent with each request to our backend so we can:

- Validate that you watched an ad before serving you a level (single-use ad reward token)
- Track your subscription status if you purchase Premium
- Record your Daily Challenge score on the global leaderboard (the leaderboard displays an anonymous alias derived from your device ID — the raw ID is never shown publicly)
- Enforce a per-day generation cap to prevent abuse
- Enforce the once-per-day free Daily Challenge attempt

The device ID is **not** the Android Advertising ID and is not shared with advertisers. If you uninstall the App, the device ID is destroyed.

### 1.2 Subscription receipts
If you subscribe to Premium, the Google Play purchase token for that subscription is sent to RevenueCat (our subscription validator) and to our backend solely to confirm that your subscription is active. We store the expiry timestamp keyed by your device ID.

### 1.3 Local game state
The App stores the following information on your device only (never sent to our backend):

- Lifetime stats (games played, wins, losses, best survival time, streak, per-mode breakdown)
- Settings (e.g. hard-mode toggle for Premium users)
- Daily Challenge attempt state (whether you've used today's free attempt)
- Pending Daily Challenge score (kept locally if the network was unavailable when you finished; submitted on next launch)

You can clear this data at any time by uninstalling the App.

### 1.4 Diagnostic logs
Our backend logs request times, HTTP status codes, error messages, and IP addresses (collected automatically by Cloudflare) for debugging and abuse prevention. These logs are retained for up to 30 days.

---

## 2. Third-party services

The App uses the following third-party services. Each has its own privacy policy, linked below.

| Service | Purpose | Data they receive |
|---|---|---|
| **Google AdMob** | Showing rewarded and interstitial ads | Android Advertising ID, IP address, device model, ad interactions. AdMob is used in compliance with Google's [Families Policy](https://support.google.com/googleplay/android-developer/answer/9893335). [AdMob privacy policy](https://policies.google.com/privacy) |
| **RevenueCat** | Validating in-app subscription receipts | Device ID, purchase token, subscription metadata. [RevenueCat privacy policy](https://www.revenuecat.com/privacy) |
| **Cloudflare** | Hosting our backend Worker | IP address (automatically), request metadata. [Cloudflare privacy policy](https://www.cloudflare.com/privacypolicy/) |
| **OpenRouter / Google Gemini** | Generating game level details (theme, story, colours) on demand | Anonymous prompts only — never your device ID or any identifying information. [OpenRouter privacy](https://openrouter.ai/privacy) |
| **Google Play Services** | App distribution + in-app billing | As governed by Google. [Google Play policy](https://policies.google.com/privacy) |

We do **not** sell or share your data with brokers, marketers, or other third parties beyond those listed above.

---

## 3. How long we keep your data

- **Device ID and subscription status**: kept on our backend until your subscription expires (max 31 days from purchase per renewal), or you uninstall the App.
- **Daily Challenge leaderboard scores**: kept for 7 days, then automatically deleted.
- **Daily Challenge attempt counter**: kept for 48 hours (covers the UTC day plus clock skew), then automatically deleted.
- **Generated-level cache** (theme/story per mode): kept for 24 hours, no per-user identifying information.
- **Ad reward tokens**: single-use, deleted within minutes of creation.
- **Per-day rate-limit counters**: automatically deleted 24 hours after the last entry.
- **Diagnostic logs**: up to 30 days.

---

## 4. Children

This App is rated for ages 13+ in the Google Play Store, consistent with AdMob's terms of service. We do not knowingly collect data from children under 13. If you believe a child under 13 has used this App, please contact us at ai.infinitygames@gmail.com and we will delete any associated data.

---

## 5. Your rights

You can:
- **Stop all data collection**: uninstall the App. The device ID is destroyed on uninstall.
- **Reset your Advertising ID**: Settings → Privacy → Ads → Reset advertising ID. This severs the link AdMob can build between sessions.
- **Cancel your subscription**: through Google Play → Subscriptions.
- **Request data deletion**: email us at ai.infinitygames@gmail.com with your device ID and we will delete any record we hold within 30 days.

---

## 6. Security

Data in transit to our backend uses TLS (HTTPS). Subscription and reward records are stored in Cloudflare KV under access keys we control. We do not transmit purchase tokens to any party besides RevenueCat (for validation) and our backend.

---

## 7. International users

Our backend is operated by Cloudflare and serves users globally. If you access the App from outside your home country, your data may be processed in jurisdictions other than your own.

---

## 8. Changes to this policy

We may update this policy from time to time. The "Effective date" above will be revised, and material changes will be communicated through the App's update notes. Continued use of the App after a change constitutes acceptance of the revised policy.

---

## 9. Contact

For questions about this policy or to exercise any of the rights listed above:

**Email:** ai.infinitygames@gmail.com
**Publisher:** Infinity Games

---

*This policy is licensed under CC-BY-4.0 — feel free to adapt for your own app.*
