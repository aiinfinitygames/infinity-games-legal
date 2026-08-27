# Privacy Policy — PIXL SURF

**Effective date:** 2026-08-27
**Publisher:** Infinity Games
**Contact:** ai.infinitygames@gmail.com

This is the privacy policy for the mobile game **PIXL SURF** ("the App"), published by Infinity Games ("we", "us", "our"). It explains what data the App collects, how we use it, and which third parties receive it.

We do **not** require you to create an account, and we do **not** collect your real name, email address, phone number, contacts, photos, precise location, or advertising ID. **The App shows no ads**, contains no advertising SDK, and uses no analytics SDK — we collect no usage statistics about you at all. The one Google library the App includes is **Google Play Billing**, for the optional tip jar (Section 1.3). It brings Google's own transport component with it, which reports the billing library's own operation to Google under Google's policies; we neither receive nor read anything from it.

The App has two optional online features — a **global leaderboard** (Section 1.2) and a **PIXL CODE** profile sync that carries your settings between our games (Section 1.2b). The App is fully playable with neither of them.

---

## 1. Data we collect

### 1.1 Local game state (stored on your device only)
The following is stored on your device only and is **never** sent to us:

- Your best score and your local list of recent high scores
- The display name you last entered for the leaderboard
- Audio (sound) and haptics (vibration) settings
- Your selected cosmetics (handheld shell theme and board skin)
- Your best medal earned
- A **random device identifier** (see Section 1.2a)
- Your **PIXL CODE**, if you have made or entered one (see Section 1.2b)

You can clear this data at any time by uninstalling the App.

### 1.2 Leaderboard data (only if you submit a score)
The App includes an optional **global leaderboard**. If — and only if — you choose to submit a score, the App sends the following to our leaderboard service:

- The **display name you type in** (a short nickname of your choosing, up to 12 characters)
- Your **score**
- A **timestamp** of the submission
- A **random device identifier** (see Section 1.2a)
- A **signature** computed from the above, which exists only to make casual score forgery harder

This information is **publicly visible** to other players on the in-game leaderboard. **Please do not enter your real name or any personal information as your display name** — pick a nickname.

To operate the leaderboard and prevent spam and cheating, our service provider (**Cloudflare**) processes your **IP address** transiently for rate-limiting. We do not store your IP address as part of your leaderboard entry, and we do not use it to identify or track you.

### 1.2a The random device identifier
On first run the App generates a **random 16-character hexadecimal string** and stores it on your device. It is **not** your advertising ID, Android ID, IMEI, MAC address, or any other hardware or system identifier, and it cannot be linked back to your handset by us or anyone else.

It exists for one reason: so that a display name can be **reserved to the handheld that first used it**, which is what stops another player claiming your name on the leaderboard. Our leaderboard service stores it alongside the name for that purpose, and it is sent with a score and when the App checks whether a name is free.

If you uninstall the App, this identifier is destroyed and a new one is generated on reinstall. You will no longer be recognised as the owner of a name you previously reserved.

We do **not** collect your advertising ID, Android ID, or any hardware identifier.

### 1.2b PIXL CODE profile sync (only if you create or enter a code)
Our games share a settings profile so that a shell theme you choose in one is the theme you get in another. If — and only if — you create a **PIXL CODE** or type one in, the App sends and retrieves the following:

- The **PIXL CODE** itself: six characters, randomly generated. It is **not** derived from your device, your name, or anything about you
- Your **random device identifier** (see Section 1.2a)
- Your **settings**: shell theme, display name, sound on/off, haptics on/off
- A **timestamp** and a **signature**

That is the complete list. The sync carries **preferences and nothing else** — not your best score, not your local high-score list, not your medals. Every cosmetic in these games is free, so there is nothing in a profile worth stealing.

A PIXL CODE is **not secret and not a password**. Anyone who types your code into one of our games can read and overwrite the settings stored under it. Do not treat it as a login. The App says so on the screen where the code is shown.

### 1.3 In-app purchases (optional tips)
If you choose to leave an optional **tip** to support the developer, the transaction is handled by **Google Play Billing**. Tips unlock nothing and grant no advantage — they are purely a way to say thanks; all cosmetics in the App are free. We receive confirmation of the purchase from Google; we do **not** receive or store your payment-card details.

Including Play Billing adds two things to the App: the `com.android.vending.BILLING` permission, and `ACCESS_NETWORK_STATE`, which the billing library uses to check whether the device is online. Neither gives us any new access to you — `ACCESS_NETWORK_STATE` reports only whether a connection exists, not what you do with it. The billing library also carries Google's own transport component, which sends Google diagnostics about the library's operation; that is Google's collection, under Google's policies, and it is not routed to us.

**Refunds are handled by Google Play**, not by us.

---

## 2. Third-party services

| Service | Purpose | Data they receive |
|---|---|---|
| **Cloudflare** | Hosts our leaderboard and PIXL CODE profile backend backend (Workers + KV storage) | The display name, score, and timestamp you submit; your IP address (transiently, for rate-limiting). [Cloudflare privacy policy](https://www.cloudflare.com/privacypolicy/) |
| **Google Play Services** | App distribution + in-app billing (tips) | As governed by Google. [Google Play policy](https://policies.google.com/privacy) |

We do **not** sell or share your data with advertisers, data brokers, marketers, or any other third parties beyond those listed above. There is no advertising network in the App, and no analytics SDK of ours — see the note on Google Play Billing's own transport component in Section 1.3.

---

## 3. How long we keep your data

- **Local game state**: kept on your device until you uninstall the App or clear its data. We never receive it.
- **The random device identifier**: retained by our leaderboard service alongside your leaderboard entry, so the name stays reserved to you. Destroyed on your device when you uninstall; you may request removal of the server-side copy by contacting us.
- **PIXL CODE profiles**: your code, device identifier and settings are retained so the code keeps working. You may request removal by contacting us.
- **Leaderboard entries**: your submitted display name, score, and timestamp are retained by our leaderboard service so the leaderboard can be shown. You may request removal of an entry by contacting us (see Section 7).
- **IP address**: processed transiently by Cloudflare for rate-limiting and not retained as part of your entry.

---

## 4. Children

This App does not knowingly collect personal data from children. Because the leaderboard display name is chosen by the player, we ask all players — and especially younger ones — not to use their real name or any personal information as their nickname. If you believe a child has submitted personal information, contact us at ai.infinitygames@gmail.com and we will remove the entry.

---

## 5. Your rights

You can:
- **Stop all data collection**: don't submit a leaderboard score (the App is fully playable offline), and/or uninstall the App.
- **Remove a leaderboard entry**: email us and we will delete it.
- **Make a privacy request**: email us at ai.infinitygames@gmail.com.

Depending on your region (e.g. EEA/UK under GDPR, California under CCPA/CPRA), you may have additional rights to access, correct, delete, or restrict processing of your data.

---

## 6. Security

Data submitted to the leaderboard is sent over an encrypted connection (HTTPS/TLS) and is signed to prevent tampering. Your game progress is kept on your device and is not transmitted to us except for the leaderboard fields described in Section 1.2.

---

## 7. International users

Our leaderboard provider (Cloudflare) and Google operate globally. If you access the App from outside your home country, the data described above may be processed in jurisdictions other than your own.

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
