# Privacy Policy — Neon Bluff

**Effective date:** 2 May 2026
**Last updated:** 2 May 2026

---

## The short version

Neon Bluff does not ask you to create an account. We do not run our own backend server. We do not use analytics or crash reporting. We do not track you across other apps or websites.

The one thing that's different from a fully offline game: Neon Bluff shows ads. Ads are served by **Google AdMob**, which may collect a device-level advertising identifier (IDFA) if you allow it. iOS will ask you on first launch via the standard App Tracking Transparency prompt, and **declining is fine** — the game still works, ads just become non-personalised.

Game Center is optional. Sign in if you want leaderboards; skip it if you don't.

---

## The longer version

### What the app stores on your device

The following are kept on your iPhone using `UserDefaults`, the standard iOS on-device key/value store:

- Your highest score
- Your sound and haptics preferences
- A flag remembering that you've seen the App Tracking Transparency prompt (so we don't show it twice)

This information never leaves your device. It's covered under Apple's `NSPrivacyAccessedAPICategoryUserDefaults` declaration with reason code `CA92.1` ("Access info from same app, per the app's functionality").

If you delete Neon Bluff from your iPhone, this on-device information is erased.

### Advertising — Google AdMob

To support the free version, Neon Bluff includes **Google AdMob** (Google's Mobile Ads SDK).

- **Ad formats used:** rewarded video (you opt in to watch an ad in exchange for a continue) and interstitial (full-screen ad shown between runs).
- **Data AdMob may process:** the IDFA advertising identifier (only if you allow tracking via the iOS prompt), coarse device information, IP address, ad interactions. AdMob's full privacy practices are described here: <https://support.google.com/admob/answer/6128543> and <https://policies.google.com/privacy>.
- **App Tracking Transparency:** on first launch the iOS prompt asks whether Neon Bluff may track you across other companies' apps and websites. **If you tap "Ask App Not to Track,"** AdMob serves non-personalised ads only and does not receive your IDFA. **If you tap "Allow,"** AdMob may receive your IDFA and serve personalised ads.
- **Children:** Neon Bluff is rated 4+. We do not knowingly serve interest-based advertising to users under 13. Parents can decline the ATT prompt to ensure non-personalised ads only.

You can revisit your tracking decision any time at *Settings → Privacy & Security → Tracking*, or *Settings → Neon Bluff* on your iPhone. You can also reset your advertising identifier any time at *Settings → Privacy & Security → Tracking → Reset Advertising Identifier*.

### Game Center

If you sign into Apple's Game Center to use leaderboards or achievements, your Game Center alias and score data are sent to Apple's Game Center service. We see only the score numbers and the alias Apple shows us — never your real name, email, or Apple ID. Game Center is operated by Apple under their privacy terms: <https://www.apple.com/legal/privacy/>. You can sign out of Game Center any time from *Settings → Game Center* on your iPhone.

### What the app does *not* do

- We do not collect, store, or transmit any personally identifying information ourselves.
- We do not use cookies, web beacons, analytics pixels, or device fingerprints.
- We do not embed any third-party analytics or crash-reporting SDKs (Firebase, Crashlytics, Mixpanel, Amplitude, etc. are all absent).
- We do not require you to create an account or provide an email address to play.
- We do not access your location, contacts, photos, microphone, camera, Bluetooth, or health data.
- We do not make network requests during gameplay other than the ad requests Google AdMob makes to fetch ads.

### Children's privacy

Neon Bluff is rated **4+** on the App Store. The game contains no inappropriate content. We do not knowingly collect or solicit data from children under 13. AdMob is configured to request only general-audience ad content (`MaxAdContentRating: G`) and to apply Google's "tag for users under the age of consent" treatment by default in regions where that designation applies, which restricts the use of advertising identifiers and personalised ads for those users. Declining the App Tracking Transparency prompt also ensures only non-personalised ads are served, regardless of region.

### Users in the European Economic Area, the United Kingdom, and Switzerland

Under the GDPR and the UK GDPR, you have the right to access, correct, or delete personal data held about you, and to object to processing. Because Neon Bluff itself does not collect or hold personal data, requests of this nature are most usefully directed to Google for the AdMob data described above. Google's instructions are at <https://policies.google.com/privacy?hl=en> and <https://support.google.com/admob/answer/7666366>. The lawful basis for AdMob's processing of advertising identifiers is your consent, gathered via the iOS App Tracking Transparency prompt. If you decline, no advertising identifier is shared and ads are non-personalised.

### Users in California

Under the California Consumer Privacy Act and California Privacy Rights Act, California residents have rights to know, delete, correct, and opt out of the "sale" or "sharing" of personal information. Neon Bluff does not sell personal information. Whether AdMob's use of advertising identifiers for personalised ads constitutes "sharing" under California law depends on Google's determinations and your consent choice. To opt out of personalised ads at the device level, decline the App Tracking Transparency prompt or change the setting at *Settings → Privacy & Security → Tracking*.

### Changes to this policy

If we materially change how Neon Bluff handles data, we will update this page and bump the "Last updated" date at the top. Continued use of the app after a change constitutes acceptance.

### Contact

If you have any questions about privacy, this policy, or anything Neon Bluff related:

Email: **shreekaanth.s@gmail.com**

We read every message.

---

*Neon Bluff. A reflex game where the words lie.*
