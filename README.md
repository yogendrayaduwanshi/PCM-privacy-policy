# PCM – Personalize Call Manager

PCM (Phone Call Manager) is a lightweight Android utility app designed to provide better awareness of incoming calls without interfering with normal call behavior.

The app focuses on transparency and user control, offering call-related insights and optional informational notifications while ensuring calls continue as usual.

---

## Features

- Displays useful call-related information in a simple interface  
- Detects repeated calls from unknown numbers  
- Shows optional, non-intrusive notifications for repeated calls  
- Does not block, record, or modify calls  
- Clean and minimal user interface  

---

## Behavior & Limitations

- PCM **does not block any calls**
- PCM **does not auto-reject unknown callers**
- Notifications are **informational only**
- All call handling remains under the system dialer and user control

---

## Privacy

PCM is built with privacy as a priority.

- No personal data is collected or stored
- No data is transmitted to external servers
- All processing happens locally on the device
- Permissions are used only for core app functionality

For more details, see the [Privacy Policy](./index.md).

---

## Permissions Used

PCM may request the following permissions depending on enabled features:

- Phone-related permissions (for call awareness)
- Contacts access (only if explicitly enabled by the user)
- Notification permission (for optional alerts)

These permissions are required solely to provide app functionality and are not used for tracking or advertising.

---

## Tech Stack

- Language: Kotlin / Java
- Platform: Android
- Architecture: Activity / Fragment based
- Build System: Gradle
- IDE: Android Studio

---

## Installation

1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle
4. Build and run on a physical device or emulator

---

## Release & Distribution

- Distributed using Android App Bundle (AAB)
- Optimized with code shrinking and resource optimization
- Prepared for Google Play Store compliance

---

## Disclaimer

PCM is a utility app intended to assist users with call awareness.  
It does not replace the system dialer or telecom services and does not guarantee caller identity verification.

---

## Contact

For questions or support, please contact:

**Email:** personalizecallmanager@gmail.com
