# Privacy Policy & Terms of Use — FlickKeyboard

**Last Updated:** April 21, 2026

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

- **Downloading voice recognition models** — an optional offline AI model (~225 MB, GigaAM V3 with punctuation) for voice input. This is a one-time download initiated only by user action in Settings.

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

## 12. Your Rights as a Data Subject

Even though FlickKeyboard does not collect, transmit, or store personal data on external servers, applicable laws (GDPR, PIPL, Federal Law No. 152-FZ) grant you the following rights regarding any data that could be associated with you:

- **Right to be informed** — this document informs you of all data practices of the App (which reduce to "nothing leaves your device").
- **Right of access** — you can inspect all data stored locally by the App via system file-manager in the App's sandbox, or by exporting from Settings (where available).
- **Right to rectification** — you can modify keyboard settings, user dictionary, and recent emoji directly in the App. There is no server-side data to correct.
- **Right to erasure** — you can clear all locally stored data at any time by **uninstalling the App**, or by deleting the voice recognition model in Settings.
- **Right to restrict processing** — you can disable any feature (voice input, swipe typing, predictions, etc.) via in-keyboard settings. Microphone permission can be revoked in system settings.
- **Right to data portability** — since the App does not collect personal data, there is nothing to transfer. User dictionary and settings are local and can be backed up via HarmonyOS system backup.
- **Right to object** — you can stop using the App at any time by uninstalling it.
- **Right to withdraw consent** — microphone access and internet access can be revoked in system settings without losing core keyboard functionality.

Because no personal data is transmitted to or stored by the developer, most rights requests (access, deletion, portability) are fulfilled directly by the App's local storage model. For any questions regarding these rights, contact the developer at **th1ng.app@mail.ru**. We respond within 30 days in accordance with GDPR Article 12.

## 13. Contact

If you have questions about this Privacy Policy or your data subject rights, contact us at:

📧 **th1ng.app@mail.ru**

---

*© 2026 Th1ng. All rights reserved.*
