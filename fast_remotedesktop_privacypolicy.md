# Fast Remote Desktop - Privacy Policy

**Last updated: 27 September 2026**

Fast Remote Desktop is designed as a privacy-first, local-first app for controlling your own computers remotely over VNC (including macOS Screen Sharing). This policy explains what information Fast Remote Desktop handles, what it does not collect, and how your data is stored.

## 1. Overview

Fast Remote Desktop connects your device directly to the computers you add. Your remote screen, keyboard and mouse input, clipboard, and files travel directly between your device and your computer — they do not pass through any developer server.

- No user accounts or sign-in.
- No advertising SDKs.
- No analytics or tracking SDKs.
- No developer-operated cloud backend or relay for your computers, credentials, screens, or files.

Your saved computers, credentials, trusted host keys, and app preferences are stored on your device.

## 2. Data We Collect

Fast Remote Desktop does not collect personal data directly through developer servers.

Specifically, Fast Remote Desktop does not directly collect or transmit to the developer:

- Your name, email, phone number, or contact details.
- Your computer addresses, user names, passwords, or SSH keys.
- The contents of your remote screen, your keystrokes, or your clipboard.
- The files you browse, send, or download.
- Your usage analytics or behavior tracking data.

## 3. On-Device Data Storage

Fast Remote Desktop stores app data locally on your device.

This includes, for example:

- Saved computer profiles (such as a display name, address, port, user name, display layout, and connection options) stored in the app's local key-value preferences.
- Passwords, SSH passwords, SSH private keys, and key passphrases stored separately in the platform secure store — the iOS Keychain or Android's Keystore-backed encrypted storage — and never in plain-text preferences.
- SSH host key fingerprints you have chosen to trust, used to detect if a computer's identity changes.
- App preferences, such as touch mode, trackpad sensitivity, clipboard sync, keep screen on, dark mode, and whether you have completed the introduction tour.
- Subscription status cache and free-tier usage state (for example, when your next free session becomes available). No purchase receipt is stored.

Deleting a saved computer also deletes its stored credentials. If you uninstall Fast Remote Desktop, locally stored app data may be removed according to your platform's behavior.

## 4. Computers, Credentials, and Remote Sessions

Fast Remote Desktop connects to computers that you add, so you can see and control their screens.

- The addresses and credentials you enter are used only to connect to those computers.
- Credentials are stored in your device's secure store and are sent only to the computer you are connecting to.
- Your remote screen is streamed directly to your device for display. It is not recorded, saved, or uploaded to any developer server.
- Keyboard, mouse, and touch input you make during a session is sent only to the computer you are controlling.
- While a session is not visible (for example, while the app is in the background), the screen stream is paused.

**Encryption:** Standard VNC connections are not encrypted, and Apple's account sign-in protects only your credentials. For an encrypted connection, you can turn on the optional SSH tunnel, which encrypts the whole session between your device and your computer. The first time you connect over SSH, the app shows you the computer's host key and remembers it only if you accept it.

## 5. Clipboard Sync

When clipboard sync is on (it is on by default and can be turned off in Settings), text you copy on your remote computer can be placed on your device's clipboard, and text on your device's clipboard can be sent to the remote computer during a session.

- Clipboard text is exchanged only between your device and the computer you are connected to.
- It is not stored by the app or sent to any developer server.

## 6. Finding Computers on Your Local Network

Fast Remote Desktop can show computers on your local network that offer screen sharing or SSH (using standard Bonjour / mDNS discovery).

- Discovery messages stay on your local network and are not sent to any developer server.
- Discovered computers are not saved unless you choose to add one.

Your device may request local network permission for this. You can change this permission at any time in your device settings.

## 7. File Transfer

Fast Remote Desktop can browse, send, download, share, rename, and delete files on your computer using SFTP over that computer's own SSH service (on a Mac, Remote Login).

- Files move directly between your device and your computer over an encrypted SSH connection.
- Files you send are chosen by you through your device's file picker, and are read only to be sent.
- When you download a file to share or save, a temporary copy is created on your device and deleted once the share or save has finished, been cancelled, or failed.
- You choose where downloaded files are saved or shared. Once you share a file with another app or service, that destination handles the file under its own terms.

## 8. In-App Purchases

Fast Remote Desktop can be used for free within limits, and offers an optional Pro subscription that removes those limits.

Purchases are processed by your platform store provider, such as:

- Apple App Store
- Google Play

Important details:

- Payment processing is handled by the store, not by the Fast Remote Desktop developer.
- Fast Remote Desktop may receive purchase status/entitlement signals from the store so features can be unlocked or restored.
- Fast Remote Desktop does not receive your full payment card details.

Your transactions with Apple or Google are governed by their terms and privacy policies.

## 9. Network Access and Connectivity

Fast Remote Desktop's core purpose involves network activity, but that activity is between your device and your computers.

Network activity may occur for the following reasons:

- Connecting to and controlling the computers you add, directly or through an SSH tunnel.
- Transferring files with your computers over SSH.
- Optional discovery of computers on your local network.
- In-app purchase flows and restore checks through Apple/Google services.
- App distribution, updates, and store infrastructure operations.

Fast Remote Desktop does not run a developer backend that receives your computers, credentials, screens, input, or files.

## 10. Third-Party Services and SDKs

Fast Remote Desktop uses essential platform and framework components to function (for example, the Flutter runtime, open-source SSH and cryptography libraries that run on your device, the platform secure store, and app store billing infrastructure).

Fast Remote Desktop does not include third-party advertising or analytics SDKs for user tracking.

Where third-party platform services are involved (such as Apple/Google purchase services), those providers process data under their own policies.

## 11. Children's Privacy

Fast Remote Desktop is a general-audience app and is not directed specifically to children.

Because Fast Remote Desktop does not operate developer servers to collect personal data from users, the developer does not knowingly collect personal data from children through Fast Remote Desktop.

If you are a parent or guardian and have concerns, you can remove app data by deleting app data or uninstalling the app on the device.

## 12. Your Control Over Data

Because Fast Remote Desktop data is stored locally on your device:

- You can edit or remove saved computers, their credentials, and other in-app data within the app.
- You can turn clipboard sync off in Settings.
- You can clear local app data using your device/app settings.
- You can uninstall the app to remove locally stored data (subject to device backup behavior).

## 13. Data Security

Fast Remote Desktop stores passwords and SSH keys in the platform secure store (iOS Keychain / Android Keystore-backed storage), verifies SSH host keys you have trusted, and uses reasonable technical measures provided by the platform and app framework for local data handling.

No software environment is perfectly secure. You are responsible for device-level security controls such as passcodes, biometrics, operating system updates, and backup settings, and for the security of your own computers and network — including choosing to use the SSH tunnel when connecting over networks you do not trust.

## 14. Changes to This Policy

If Fast Remote Desktop data practices change, this policy will be updated.

When updates happen, the "Last updated" date at the top of this document will be revised.

## 15. Contact

For privacy questions about Fast Remote Desktop, contact:

Email: uaua.ltd+fastremotedesktop@gmail.com
