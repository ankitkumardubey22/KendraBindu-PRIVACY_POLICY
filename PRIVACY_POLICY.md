# Privacy Policy — KendraBindu

**Last updated:** 29 April 2026
**App:** KendraBindu 

KendraBindu collects **no personal data**. Everything you create — habits,
notes, expenses, mantras, photos — stays on your phone in the device's
local storage. The app does not have a server, does not have an account
system, does not include any analytics or tracking SDK,
and does not make network requests for the core experience.

If that's enough for you, you can stop reading. The rest of this page just
spells out the same thing in detail, because the app stores require it.

---

## 1. What data the app handles

The app stores the following information **on your device only**, in the
operating system's local storage:

* Habits, todos, notes, study sessions, expenses, meals, moments,
  mantras, reminders — everything you type or tap into the app.
* App preferences such as your selected theme and feature toggles.
* If you enable PIN lock: a cryptographic hash of your PIN (not the PIN
  itself), with a per-install random salt, stored in the operating
  system's secure keystore (iOS Keychain / Android Keystore).
* Photos you attach to Moments are stored in the app's private file
  directory; they are not uploaded anywhere.

## 2. Data the app does NOT collect

* **No personal identifiers** — no email, phone number, name, address.
* **No device identifiers** — no IDFV, no GAID
  collection.
* **No analytics or telemetry** — the app contains no analytics SDK and
  no crash reporting service.
* **No location data.**
* **No contacts, calendar, or third-party app data.**
* **No sound or microphone recording.** The Mantra / Jap feature counts
  taps; it does not listen.

## 3. Permissions the app asks for, and why

| Permission                        | Why                                                |
|-----------------------------------|----------------------------------------------------|
| Notifications                     | To deliver the local reminders you set yourself.   |
| Schedule exact alarm (Android)    | To deliver mantra / habit reminders precisely on time. |
| Vibrate / wake lock               | To play the alarm overlay reliably.                |
| Camera (only when you tap "add photo") | To capture an image for a Moment.             |
| Photo library (only when you tap "add photo") | To pick an image for a Moment.         |

All permissions are optional. If you decline, the app still works — only
the corresponding feature is disabled.

## 4. Network access

The app makes no network requests for any core feature. It will continue
to work fully even with airplane mode on. If a future version introduces
an optional online feature (for example, AI summarisation), it will be
clearly marked as optional, and this policy will be updated **before**
that feature is released.

## 5. Children

The app is suitable for all ages. It does not collect any personal
information from anyone, including children under 13.

## 6. Data retention and deletion

Because no data leaves your device:

* Uninstalling the app removes all stored data.
* "Reset app data" inside Settings (if available) wipes the local
  database and starts fresh.
* There is no server-side data to request, export, or delete.

## 7. Security

* All sensitive secrets (the PIN hash, the salt) are stored in the
  operating system's secure keystore.
* The app's database is stored in the app's private sandbox, which on
  modern iOS and Android is encrypted at the OS level when device-level
  encryption (lock screen) is enabled.
* No additional encryption-at-rest is provided beyond the OS layer.

## 8. Third-party services

The app uses the following open-source libraries; none of them transmit
your data:

* React Native, Expo SDK 54
* expo-sqlite (local database)
* expo-secure-store (PIN hash storage)
* expo-notifications (local notifications)
* expo-image-picker, expo-file-system, expo-haptics, expo-linear-gradient
* @react-navigation/native and friends
* react-native-gifted-charts, react-native-svg

The full list lives in the project's `package.json`.

## 9. Changes to this policy

If we change anything, we will update the "Last updated" date above and
post a short note in the app's "What's New" screen.
