# Privacy Policy — PIXL SQUAD

**Effective date:** 2026-08-27
**Publisher:** Infinity Games
**Contact:** ai.infinitygames@gmail.com

This is the privacy policy for the mobile game **PIXL SQUAD** ("the App"), published by Infinity Games ("we", "us", "our"). It explains what data the App collects, how we use it, and which third parties receive it.

We do **not** require you to create an account, and we do **not** collect your real name, email address, phone number, contacts, photos, precise location, or advertising ID. **The App shows no ads**, contains no advertising SDK, and uses no analytics SDK — we collect no usage statistics about you at all. The one Google library the App includes is **Google Play Billing**, for the optional tip jar (Section 1.6). It brings Google's own transport component with it, which reports the billing library's own operation to Google under Google's policies; we neither receive nor read anything from it.

The App contains an optional **tip jar** (Section 1.6). Tips are voluntary, they unlock nothing, and payment is handled entirely by Google Play — we never see your card or your billing details.

The App has two optional online features — a **global leaderboard** and a **PIXL CODE** profile sync that carries your settings between our games. Both are described below. The App is fully playable with neither of them.

---

## 1. Data we collect

### 1.1 Local game state (stored on your device only)
The following is stored on your device only and is **never** sent to us:

- Your campaign: which mission you have reached, your squad's names, ranks and specialisms, who you have lost, and your sugar bank
- Which kit you have bought (bombs, rushes, glow grubs, bubbles, traps)
- Which briefing notes you have already been shown
- Audio (sound) and haptics (vibration) settings
- Your selected handheld shell theme
- The display name you last entered
- A **random device identifier** (see Section 1.4)

You can clear all of it by uninstalling the App.

### 1.2 Leaderboard data (only if you submit a score)
The App has two boards — a **Daily Supply Run** board and a **campaign** board. If — and only if — you choose to submit a score, the App sends the following to our leaderboard service:

- The **display name you type in** (a short nickname of your choosing, 2 to 12 characters)
- Your **score**
- A **timestamp** of the submission
- The number of **flies you have lost** in your campaign, which is shown as a family-wide tally
- Which **board** the score is for
- Your **random device identifier** (see Section 1.4)
- A **signature** computed from the above, which exists only to make casual score forgery harder

Your display name, score and lost-tally are **publicly visible** to other players on the in-game leaderboard. **Please do not enter your real name or any personal information as your display name** — pick a nickname.

### 1.3 PIXL CODE profile sync (only if you create or enter a code)
Our games share a settings profile so that a theme you choose in one is the theme you get in another. If — and only if — you create a **PIXL CODE** or type one in, the App sends and retrieves the following:

- The **PIXL CODE** itself: six characters, randomly generated. It is **not** derived from your device, your name, or anything about you
- Your **random device identifier** (see Section 1.4)
- Your **settings**: shell theme, display name, sound on/off, haptics on/off
- A **timestamp** and a **signature**

That is the complete list. The sync carries **preferences and nothing else** — no campaign progress, no purchases, no entitlements. Every cosmetic in these games is free, so there is nothing in a profile worth stealing.

A PIXL CODE is **not secret and not a password**. Anyone who types your code into one of our games can read and overwrite the settings stored under it. Do not treat it as a login.

### 1.4 The random device identifier
On first run the App generates a **random 16-character hexadecimal string** and stores it on your device. It is **not** your advertising ID, Android ID, IMEI, MAC address, or any other hardware or system identifier, and it cannot be linked back to your handset by us or anyone else.

It exists for one reason: so that a display name and a PIXL CODE can be **reserved to the handheld that first used them**, which is what stops another player claiming your name or overwriting your profile. Our leaderboard service stores it alongside the name and the code for that purpose.

If you uninstall the App, this identifier is destroyed and a new one is generated on reinstall. You will no longer be recognised as the owner of a name or code you previously reserved.

### 1.5 IP address
To operate the service and prevent spam and cheating, our provider (**Cloudflare**) processes your **IP address** transiently for rate-limiting. We do not store your IP address as part of your leaderboard entry or your profile, and we do not use it to identify or track you.

### 1.6 Tips (only if you choose to give one)
The App has a **TIP JAR** screen. It is entirely optional and it is the only place in the App where money changes hands.

**A tip unlocks nothing.** There is no cosmetic, no character, no currency, no shortcut and no badge attached to it. Nothing in the game is locked behind anything, before or after a tip, and the game's save file is byte-for-byte identical either way.

If you choose to give a tip:

- The purchase is processed by **Google Play Billing**. Google is the seller of record. **We never receive or see your payment card, bank details, or billing address** — Google does not give them to us.
- Google returns to the App a **product identifier** (which tier you chose) and a **purchase token**. The App uses the token once, to mark the purchase as consumed with Google, and then discards it.
- **Neither the product id nor the purchase token is stored on your device or sent to our leaderboard service.** Nothing about a tip appears in your PIXL CODE profile, on the leaderboard, or in your save file.
- Tips are **consumable** products, which means they can be given more than once. They are not a purchase you "own" and there is nothing to restore.

Including Play Billing adds two things to the App that were not in it before: the `com.android.vending.BILLING` permission, and `ACCESS_NETWORK_STATE`, which the billing library uses to check whether the device is online. Neither gives us any new access to you — `ACCESS_NETWORK_STATE` reports only whether a connection exists, not what you do with it. The billing library also carries Google's own transport component, which sends Google diagnostics about the library's operation; that is Google's collection, under Google's policies, and it is not routed to us.

Google's handling of the transaction is governed by the [Google Payments privacy notice](https://payments.google.com/legaldocument?family=0.privacynotice). **Refunds are handled by Google Play**, not by us.

---

## 2. Third-party services

| Service | Purpose | Data they receive |
|---|---|---|
| **Cloudflare** | Hosts our leaderboard and profile backend (Workers + KV storage) | The fields listed in Sections 1.2 and 1.3; your IP address (transiently, for rate-limiting). [Cloudflare privacy policy](https://www.cloudflare.com/privacypolicy/) |
| **Google Play Services** | App distribution | As governed by Google. [Google Play policy](https://policies.google.com/privacy) |
| **Google Play Billing** | Processing optional tips (Section 1.6) | Your payment details, which go to Google and **not** to us. We receive only a product id and a one-use purchase token. [Google Payments privacy notice](https://payments.google.com/legaldocument?family=0.privacynotice) |

We do **not** sell or share your data with advertisers, data brokers, marketers, or any other third parties beyond those listed above. There is no advertising network in the App, and no analytics SDK of ours — see the note on Google Play Billing's own transport component in Section 1.6.

**The App's only in-app purchases are optional tips, and they unlock nothing** (Section 1.6). Every cosmetic, mission, fly and piece of kit in the game is reachable without spending anything.

---

## 3. How long we keep your data

- **Local game state**: kept on your device until you uninstall the App or clear its data. We never receive it.
- **Leaderboard entries**: your display name, score, timestamp, lost-tally and device identifier are retained so the leaderboard can be shown. Each name holds one entry — its best score. You may request removal by contacting us (see Section 7).
- **PIXL CODE profiles**: your code, device identifier and settings are retained so the code keeps working. You may request removal by contacting us.
- **IP address**: processed transiently by Cloudflare for rate-limiting and not retained.
- **Tips**: we retain nothing. The purchase token is used once to consume the purchase and then discarded; it is not written to your device or sent to our service. Google retains its own record of the transaction under its policies.

---

## 4. Children

This App does not knowingly collect personal data from children. Because the leaderboard display name is chosen by the player, we ask all players — and especially younger ones — not to use their real name or any personal information as their nickname. If you believe a child has submitted personal information, contact us at ai.infinitygames@gmail.com and we will remove the entry.

---

## 5. Your rights

You can:
- **Stop all data collection**: don't submit a score and don't create or enter a PIXL CODE. The App is fully playable offline, and the whole campaign works with no network at all.
- **Remove a leaderboard entry or a PIXL CODE profile**: email us and we will delete it.
- **Make a privacy request**: email us at ai.infinitygames@gmail.com.

Depending on your region (e.g. EEA/UK under GDPR, California under CCPA/CPRA), you may have additional rights to access, correct, delete, or restrict processing of your data.

---

## 6. Security

Everything sent to our service goes over an encrypted connection (HTTPS/TLS) and is signed to make tampering harder. Your campaign is kept on your device and is never transmitted to us. The signing key is embedded in the App; it raises the cost of forging a score and should not be relied on as a security boundary for anything else — which is why the service holds nothing but nicknames, scores and preferences.

---

## 7. International users

Our provider (Cloudflare) and Google operate globally. If you access the App from outside your home country, the data described above may be processed in jurisdictions other than your own.

---

## 8. Changes to this policy

We may update this policy from time to time. The "Effective date" above will be revised, and material changes will be communicated through the App's update notes.

---

## 9. Contact

For questions about this policy or to exercise any of the rights listed above:

**Email:** ai.infinitygames@gmail.com
**Publisher:** Infinity Games

---

*This policy is licensed under CC-BY-4.0 — feel free to adapt for your own app.*
