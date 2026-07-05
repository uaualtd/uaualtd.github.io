# RTSP Viewer - Privacy Policy

**Last updated: 5 July 2026**

RTSP Viewer is designed as a privacy-first, local-first app for watching your own RTSP camera streams. This policy explains what information RTSP Viewer handles, what it does not collect, and how your data is stored.

## 1. Overview

RTSP Viewer is built around local, on-device usage. Video from your cameras travels directly between your device and your cameras — it does not pass through any developer server.

- No user accounts or sign-in.
- No advertising SDKs.
- No analytics or tracking SDKs.
- No developer-operated cloud backend for your cameras, credentials, or video.

Your camera list, stream URLs, credentials, recordings, and app preferences are stored on your device.

## 2. Data We Collect

RTSP Viewer does not collect personal data directly through developer servers.

Specifically, RTSP Viewer does not directly collect or transmit to the developer:

- Your name, email, phone number, or contact details.
- Your camera addresses, stream URLs, camera usernames, or camera passwords.
- Your video streams, recordings, snapshots, or thumbnails.
- Your usage analytics or behavior tracking data.

## 3. On-Device Data Storage

RTSP Viewer stores app data locally on your device.

This includes, for example:

- Camera stream configurations (such as a display name and RTSP stream URL) stored in the app's local key-value preferences.
- Camera credentials (usernames and passwords) stored separately in the platform secure store — the iOS Keychain or Android's encrypted storage — rather than in plain-text preferences.
- Recordings you capture, saved as video files in the app's private storage, along with a local SQLite index and generated thumbnail images.
- App preferences and display choices.
- Premium entitlement cache state used for purchase restoration behavior.

If you uninstall RTSP Viewer, locally stored app data may be removed according to your platform's behavior.

## 4. Cameras, Credentials, and Video

RTSP Viewer connects to cameras that you add, on your own network, so it can display and optionally record their streams.

- The camera addresses and credentials you enter are used only to connect to those cameras.
- Credentials are stored in your device's secure store and are sent only to the cameras you are connecting to, over your network.
- Video and audio from your cameras are streamed directly to your device for viewing. They are not uploaded to any developer server.
- Recordings and snapshots are stored locally in the app's private storage on your device.

## 5. Camera Discovery on Your Local Network

RTSP Viewer can optionally scan your local network to help you find compatible cameras (using standard WS-Discovery and ONVIF requests).

- Discovery messages are sent over your local network to locate cameras and read their stream information.
- This activity stays on your local network and is not sent to any developer server.
- Discovery runs only when you choose to scan for cameras.

Your device may request local network permission before a scan can run. You can change this permission at any time in your device settings.

## 6. Recordings, Sharing, and Exports

RTSP Viewer can save recordings and let you export or share them.

- Recordings are created and stored on your device.
- When you share or save a recording, it is handled through your device's native share and file system, under your control.
- You choose where exported files are sent or saved. Once you share a file with another app or service, that destination handles the file under its own terms.

You can also import a camera configuration file that you have previously exported; the file you pick is read locally on your device.

## 7. In-App Purchases

RTSP Viewer offers an optional Pro upgrade (for example, a higher camera limit and additional features), available as a subscription or one-time purchase.

Purchases are processed by your platform store provider, such as:

- Apple App Store
- Google Play

Important details:

- Payment processing is handled by the store, not by the RTSP Viewer developer.
- RTSP Viewer may receive purchase status/entitlement signals from the store so features can be unlocked or restored.
- RTSP Viewer does not receive your full payment card details.

Your transactions with Apple or Google are governed by their terms and privacy policies.

## 8. Network Access and Connectivity

RTSP Viewer's core purpose involves network activity, but that activity is between your device and your cameras.

Network activity may occur for the following reasons:

- Connecting to and streaming from the cameras you add, over your network.
- Optional discovery of cameras on your local network.
- In-app purchase flows and restore checks through Apple/Google services.
- App distribution, updates, and store infrastructure operations.

RTSP Viewer does not run a developer backend that receives your cameras, credentials, or video.

## 9. Third-Party Services and SDKs

RTSP Viewer uses essential platform and framework components to function (for example, the Flutter runtime, the media playback engine used to render streams, and app store billing infrastructure).

RTSP Viewer does not include third-party advertising or analytics SDKs for user tracking.

Where third-party platform services are involved (such as Apple/Google purchase services), those providers process data under their own policies.

## 10. Children's Privacy

RTSP Viewer is a general-audience app and is not directed specifically to children.

Because RTSP Viewer does not operate developer servers to collect personal data from users, the developer does not knowingly collect personal data from children through RTSP Viewer.

If you are a parent or guardian and have concerns, you can remove app data by deleting app data or uninstalling the app on the device.

## 11. Your Control Over Data

Because RTSP Viewer data is stored locally on your device:

- You can edit or remove cameras, credentials, recordings, and other in-app data within the app.
- You can clear local app data using your device/app settings.
- You can uninstall the app to remove locally stored data (subject to device backup behavior).

## 12. Data Security

RTSP Viewer stores camera credentials in the platform secure store (iOS Keychain / Android encrypted storage) and uses reasonable technical measures provided by the platform and app framework for local data handling.

No software environment is perfectly secure. You are responsible for device-level security controls such as passcodes, biometrics, operating system updates, backup settings, and the security of your own cameras and network.

## 13. Changes to This Policy

If RTSP Viewer data practices change, this policy will be updated.

When updates happen, the "Last updated" date at the top of this document will be revised.

## 14. Contact

For privacy questions about RTSP Viewer, contact:

Email: uaua.ltd+rtspviewer@gmail.com
