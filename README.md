<p align="center">
  <img src="docs/logo-plan-ring.png" alt="Paisa Planner logo" width="420">
</p>

<h1 align="center">Paisa Planner</h1>

<p align="center"><b>Free, private money planner for India. Works offline — your data never leaves your phone.</b></p>

<p align="center">
  <a href="https://github.com/sauravsah/Paisa-Planner/raw/main/PaisaPlanner-v3.5.3-arm64.apk"><img src="docs/download-button.png" alt="Download Paisa Planner for Android (v3.5.3, about 16 MB)" width="340"></a>
</p>

<p align="center">
  For Android phones (Android 8 or newer). This is the right file for almost every phone.<br>
  <sub>Didn't work? <a href="https://github.com/sauravsah/Paisa-Planner/raw/main/PaisaPlanner-v3.5.3.apk">Try this one instead</a> (works on every phone, about 34 MB).</sub>
</p>

---

## How to install (2 minutes)

Paisa Planner is not on the Play Store yet, so you install it from this page. You download one file and open it. That's it.

**1. Tap the green Download button above.** Do this on your Android phone.

![Step 1: tap the green Download button](docs/install-step-1.png)

**2. Open the file you downloaded.** Tap it in your notifications, or open the Files app and look in Downloads.

![Step 2: open the downloaded file from notifications or the Files app](docs/install-step-2.png)

**3. If your phone says "For your security…", allow it once.** Tap **Settings**, turn on **Allow from this source**, then press back.

![Step 3: tap Settings, turn on Allow from this source, go back](docs/install-step-3.png)

**4. Tap Install, then Open. Done!** Setup takes 2 minutes and asks for no permissions.

![Step 4: tap Install, then Open](docs/install-step-4.png)

### Is this safe?

- The app has **no internet permission**. It can't send your data anywhere, even if it wanted to.
- Google Play Protect may show a warning only because the app didn't come from the Play Store. Tap **More details**, then **Install anyway**.
- The download is the same file as on the [release page](https://github.com/sauravsah/Paisa-Planner/releases/tag/v3.5.3), signed with the same key as every version since v2.0.

### Updating later

When a new version comes out, come back to this page, download the new file and open it. Tap **Update** (or **Install**). It installs over the old app and **your data stays**. No need to uninstall first.

<sub>Optional: the free <a href="https://github.com/ImranR98/Obtainium">Obtainium</a> app can watch <code>github.com/sauravsah/Paisa-Planner</code> and tell you when a new version is out.</sub>

---

## Screenshots

<table>
  <tr>
    <td><img src="docs/screen-1.jpg" alt="Spends track themselves" width="200"></td>
    <td><img src="docs/screen-2.jpg" alt="Budgets that follow your salary" width="200"></td>
    <td><img src="docs/screen-3.jpg" alt="Save on purpose" width="200"></td>
    <td><img src="docs/screen-4.jpg" alt="Private by design" width="200"></td>
  </tr>
</table>

## What it does

![Paisa Planner: bank SMS in, budgets out](docs/banner.jpg)

- **Add a spend in seconds.** Type or say "200 vegetables", scan a bill, or paste a bank SMS. Hindi and Hinglish work too ("do sau sabzi").
- **Tracks spends from bank SMS, if you want.** It's optional and off at first. OTPs and personal messages are ignored.
- **Budgets that follow your salary day,** with a simple 50/30/20 starting plan and a gentle warning before you overspend.
- **Save on purpose:** savings goals, a 48-hour "park it" wishlist for impulse buys, and reminders for bills and subscriptions.
- **Cards, loans and friends:** credit card due dates, loans and EMIs, split bills, and money you lent or borrowed.
- **See the big picture:** net worth, a tax helper (old vs new regime) and a monthly "Money Story" recap.
- **Keep it safe:** fingerprint or PIN lock, encrypted backup, and CSV or PDF export.
- **English and Hindi,** with light and dark themes.

## Privacy

Everything stays on your phone. No account, no sign-up, no ads, no internet permission. Privacy policy: https://docs.google.com/document/d/1iUYxkjJ_4VVWXWgGWBGLeUpQRzRbcW5OXN6XJLUKoT0/edit?usp=sharing

## Feedback and support

Found a problem or want a feature? [Share it in this short form](https://docs.google.com/forms/d/e/1FAIpQLSfLpaZU3By-WU9KWcMSKTAuoew2hy2qFcAo1fQ6s-UV0EHFrQ/viewform) (no sign-in needed).

Support: sauravsahbrj@gmail.com

<details>
<summary><b>For developers</b></summary>

<br>

- Native Android app: Kotlin, Jetpack Compose (Material 3), Room, WorkManager, on-device ML Kit text recognition for receipts.
- Package `com.saurav.paisaplanner` · version 3.5.3 (versionCode 11) · minSdk 26 (Android 8.0) · targetSdk 36.
- Two builds of the same version: `PaisaPlanner-v3.5.3-arm64.apk` (64-bit ARM only, smaller) and `PaisaPlanner-v3.5.3.apk` (universal, every CPU type).
- Permissions: `READ_SMS` and `RECEIVE_SMS` (only asked for if you turn on SMS tracking), `POST_NOTIFICATIONS`, `USE_BIOMETRIC` / `USE_FINGERPRINT`, `WAKE_LOCK`, `RECEIVE_BOOT_COMPLETED`. No `INTERNET`.
- Signing certificate SHA-256: `70e49d10ad885f31444a9886646d52ea3b98a15f828bd39a795b135bcdbfeabc`

SHA-256 of the files:

```
cc64e2b9c6a6dd3ac9f4c7dd63a3ec68e8488752b0eacdabcb7fb203ece8e6c8  PaisaPlanner-v3.5.3-arm64.apk
576907ba4bf20ca8be4827d81cda3ae1a6b310f7dba47c984a850d20684551f4  PaisaPlanner-v3.5.3.apk
```

Check a download with `apksigner verify --print-certs PaisaPlanner-v3.5.3-arm64.apk` (Android build-tools).

</details>
