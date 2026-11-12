# Legacy Apps — Cydia repository for iOS 6

Apps for jailbroken iOS 6 devices, made to look like Apple's own.

**Add to Cydia:** open https://dmitrylaktionov.github.io/cydia/ on the device and tap “Add to Cydia”,
or add the source by hand: Cydia → Sources → Edit → Add → `https://dmitrylaktionov.github.io/cydia/`

| App | What it does |
| --- | --- |
| **Codes** | Two-factor authentication codes (TOTP), QR-code scanner |
| **Flashlight** | LED flashlight with brightness control, screen light fallback |
| **Inetometer** | Internet speed test with an analog gauge (Yandex Internetometer or Cloudflare) |

Requirements: iOS 6 with a jailbreak, 32-bit device. Tested on iPhone 4S, iOS 6.1.3.

Manual install: download a `.deb` from [`debs/`](debs/), copy it to the device and run `dpkg -i file.deb && uicache` as root.

Codes uses [quirc](https://github.com/dlbeer/quirc) by Daniel Beer (ISC license) for QR-code recognition.
