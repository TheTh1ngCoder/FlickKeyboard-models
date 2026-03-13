# Privacy Policy & Terms of Use — FlickKeyboard

**Last Updated:** March 13, 2026

## 1. Introduction

FlickKeyboard ("the App") is a custom keyboard application for HarmonyOS NEXT developed by Th1ng. This Privacy Policy describes how we handle your data.

**In short: FlickKeyboard does not collect, transmit, or store any of your personal data on external servers. Everything stays on your device.**

## 2. Data We Do NOT Collect

- ❌ **Typed text** — we do not log, record, or transmit any text you type
- ❌ **Passwords and credentials** — we have no access to password fields content
- ❌ **Contacts, messages, or personal files**
- ❌ **Location data**
- ❌ **Device identifiers** (IMEI, serial number, etc.)
- ❌ **Usage analytics or telemetry**
- ❌ **Advertising data**

## 3. Data Stored Locally on Your Device

The following data is stored **only on your device** using the system Preferences API and is never transmitted:

| Data | Purpose | Stored Where |
|------|---------|-------------|
| Keyboard settings (theme, language, toggles) | Remember your preferences | Device only |
| Learned words (user dictionary) | Improve predictions for you | Device only |
| Recent emoji | Show frequently used emoji first | Device only |
| Keyboard height preference | Remember your preferred size | Device only |

You can clear all locally stored data by uninstalling the App.

## 4. Internet Permission

The App requires Internet access **exclusively** for:

- **Downloading voice recognition models** — an optional offline AI model (~275 MB) for voice input. This is a one-time download initiated only by user action in Settings.

No other network activity occurs. The App does not contact any servers during normal keyboard use.

## 5. Microphone Permission

The App requests microphone access **only** when you use the voice input feature. Voice recognition is performed **entirely on-device** using the offline GigaAM model. Audio data is:

- Processed locally in real-time
- Never recorded or saved to files
- Never transmitted to any server
- Discarded immediately after recognition

Microphone access is requested at runtime and can be denied — the keyboard works fully without it.

## 6. Third-Party Services

FlickKeyboard does **not** integrate any:
- Analytics SDKs (no Google Analytics, no Huawei Analytics)
- Advertising SDKs
- Crash reporting services
- Social media trackers

## 7. Open Source Components

The App uses the following open-source components:

| Component | License | Purpose |
|-----------|---------|---------|
| GigaAM v3 (by SberDevices) | MIT License | Offline voice recognition model |
| sherpa-onnx (by k2-fsa) | Apache License 2.0 | Neural network inference engine |
| Silero VAD (by Silero Team) | MIT License | Voice activity detection |

Full license texts are available in the App under Settings → Open Source Licenses.

## 8. Children's Privacy

FlickKeyboard does not knowingly collect personal information from children under 13. Since the App collects no personal data at all, it is safe for users of all ages.

## 9. Regulatory Compliance

This App complies with applicable data protection regulations, including:

- **GDPR** — General Data Protection Regulation (European Union)
- **PIPL** — Personal Information Protection Law of the People's Republic of China (中华人民共和国个人信息保护法)
- **Federal Law No. 152-FZ** «On Personal Data» (Russian Federation)

Since FlickKeyboard does not collect, process, or transmit any personal data, compliance is inherently satisfied.

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last Updated" date. Continued use of the App after changes constitutes acceptance of the updated policy.

## 11. Terms of Use

FlickKeyboard is provided "as is" without warranties of any kind, express or implied. The developer is not liable for any damages arising from the use of the App, including but not limited to data loss, device malfunction, or interruption of service.

## 12. Contact

If you have questions about this Privacy Policy, contact us at:

📧 **th1ng.app@mail.ru**

---

*© 2026 Th1ng. All rights reserved.*
