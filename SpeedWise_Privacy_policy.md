# Privacy Policy for SpeedWise

**Last Updated: January 13, 2026**

**Effective Date: January 13, 2026**

---

## Introduction

Welcome to SpeedWise ("the App," "we," "our," or "us"). Your privacy is of utmost importance to us. This Privacy Policy explains how we handle information when you use our speed monitoring and trip tracking application.

**Our Core Privacy Commitment:** SpeedWise is designed with a **privacy-first approach**. **We do not collect, store, transmit, or share any of your personal data to our servers or any third parties.** All data used by the App remains exclusively on your device under your full control.

---

## Information Collection Statement

### We Do NOT Collect Data

SpeedWise is a **privacy-first application** that does **NOT**:

- ❌ **No data collection** — We do not collect any personal information
- ❌ **No analytics** — We do not track how you use the app
- ❌ **No advertising** — We do not display ads or use ad tracking
- ❌ **No third-party tracking** — We do not use any tracking SDKs
- ❌ **No servers** — We do not operate any servers that receive your data
- ❌ **No account required** — We do not require you to create an account
- ❌ **No data sharing** — We never share, sell, or rent your information to anyone

**All app functionality operates entirely on your device.** Your trip data, speed records, and preferences are stored locally and never leave your device.

---

## Device Permissions Explained

To provide speed monitoring and trip tracking features, the App requires certain device permissions. Below is a transparent explanation of each permission, why it is needed, and how it is used:

### 📍 Location Permissions

**Permissions:**
- `ACCESS_FINE_LOCATION` (Precise Location)
- `ACCESS_COARSE_LOCATION` (Approximate Location)
- `ACCESS_BACKGROUND_LOCATION` (Background Location Access)

**Purpose:** To display your current speed, track your trips, and compare your speed against posted speed limits using OpenStreetMap data.

**How It's Used:**
- Your GPS location is used to calculate your current speed in real-time
- Location data is used to query speed limit information from OpenStreetMap for your current road
- Background location access allows the app to continue tracking your trip when the screen is off or the app is in the background
- Trip data (routes, speeds, distances) is recorded locally on your device

**Privacy Assurance:** Your location data is processed entirely on your device. Location data is NEVER sent to our servers or any third parties. When querying speed limits, only your geographic coordinates are sent to OpenStreetMap's public API — no personal identifiers are included. All trip history is stored locally on your device only.

---

### 📳 Vibration Permission

**Permission:** `VIBRATE`

**Purpose:** To provide haptic feedback when you exceed speed limits or configured speed thresholds.

**How It's Used:**
- Creates vibration alerts when your speed exceeds the posted speed limit (if enabled)
- Provides tactile confirmation of speed alert triggers

**Privacy Assurance:** This is a basic hardware control permission with no data implications.

---

### 🔔 Notification Permission

**Permission:** `POST_NOTIFICATIONS`

**Purpose:** To display trip tracking status and speed alerts.

**How It's Used:**
- Shows persistent notification when tracking a trip in the background
- Displays speed limit exceeded warnings (if enabled)
- Provides trip controls (e.g., stop button) in the notification

**Privacy Assurance:** Notifications are generated and displayed locally on your device only.

---

### 🌐 Network Permissions

**Permissions:**
- `INTERNET`
- `ACCESS_NETWORK_STATE`

**Purpose:** To fetch speed limit data from OpenStreetMap and display map tiles.

**How It's Used:**
- Queries OpenStreetMap's Overpass API to retrieve speed limit information for your current road
- Downloads map imagery from OpenStreetMap tile servers to display your location visually (if map features are used)
- Checks if an internet connection is available to inform you if speed limit features will work

**Privacy Assurance:** Network access is used only for fetching publicly available road data and displaying maps. **We do not operate any servers that receive your data.** No personal information is transmitted over the network — only geographic coordinates are sent to OpenStreetMap to query road data.

---

### 🔄 Background & Boot Permissions

**Permissions:**
- `FOREGROUND_SERVICE`
- `FOREGROUND_SERVICE_LOCATION`
- `RECEIVE_BOOT_COMPLETED`
- `WAKE_LOCK`

**Purpose:** To maintain trip tracking running reliably in the background and optionally restore tracking after device restart.

**How It's Used:**
- Keeps trip tracking active even when the app is in the background or the screen is off
- Allows the app to continue recording your trip during long journeys
- Wake lock ensures accurate speed calculations during active tracking

**Privacy Assurance:** These are technical permissions that enable the app to function as a reliable speed monitoring tool. They do not involve any data collection.

---

### 📱 Bluetooth Permissions

**Permissions:**
- `BLUETOOTH` (Android 11 and below)
- `BLUETOOTH_CONNECT`

**Purpose:** To enable the optional auto-launch feature that starts the app when connecting to specific Bluetooth devices (e.g., your car's audio system).

**How It's Used:**
- Detects when your device connects to a paired Bluetooth device you have configured
- Optionally launches SpeedWise automatically for convenient hands-free operation while driving

**Privacy Assurance:** Bluetooth information is processed locally to detect configured device connections. No Bluetooth data is transmitted anywhere. This feature is entirely optional.

---

### 📺 Full Screen Intent Permission

**Permission:** `USE_FULL_SCREEN_INTENT`

**Purpose:** To display important speed alerts prominently.

**How It's Used:**
- Allows critical speed limit alerts to be displayed as full-screen notifications when your device is locked

**Privacy Assurance:** This is a display permission with no data collection implications.

---

## Third-Party Services

### OpenStreetMap

The App uses OpenStreetMap (OSM) for two purposes:
1. **Speed Limit Data:** When the speed limit feature is enabled, your geographic coordinates are sent to OpenStreetMap's Overpass API to query speed limit information for the road you're currently on.
2. **Map Tiles:** If map views are displayed, map imagery is fetched from OpenStreetMap tile servers.

**Important:** Only your location coordinates are transmitted — no personal identifiers, device information, or usage data is shared. OpenStreetMap is a non-profit organization providing free geographic data. Please refer to [OpenStreetMap's Privacy Policy](https://wiki.osmfoundation.org/wiki/Privacy_Policy) for information on how they handle these requests.

### In-App Purchases

The App offers optional premium features through Google Play Billing. Purchase transactions are processed entirely by Google. We do not receive, process, or store any payment information. Please refer to [Google's Privacy Policy](https://policies.google.com/privacy) for information on how they handle purchase data.

---

## Data Storage

All data used by SpeedWise is stored **locally on your device only**, including:
- Your trip history and statistics
- Speed records and top speed data
- App preferences and settings
- Configured Bluetooth devices for auto-launch

This data **never leaves your device**. We do not have access to any of your data.

---

## Data Sharing

Your data is **NEVER** shared with:
- Us (the developers)
- Third-party analytics services
- Advertising networks
- Any other third parties

**Period.** The only external communication is between your device and OpenStreetMap's public API for speed limit queries, which contains no personal information.

---

## Important Disclaimer: Driver Responsibility

⚠️ **IMPORTANT — PLEASE READ CAREFULLY** ⚠️

**SpeedWise is a driving aid tool only. The driver is solely responsible for:**
- Obeying all traffic laws and posted speed limits
- Safe operation of the vehicle at all times
- Paying attention to the road and driving conditions
- Making all driving decisions

**The App may display incorrect or incomplete information due to:**
- **GPS Signal Quality:** Speed and location accuracy depend on your device's GPS signal. Poor signal (tunnels, urban canyons, dense tree cover) can cause inaccurate readings.
- **OpenStreetMap Data:** Speed limit data is sourced from OpenStreetMap, a community-maintained database. This data may be:
  - Missing for certain roads
  - Outdated or incorrect
  - Not available in all regions or countries
  - Different from actual posted limits
- **Device Limitations:** Different devices have varying GPS accuracy and update frequencies.
- **Processing Delays:** There may be brief delays in speed calculations or speed limit fetches.

**YOU MUST:**
- Always observe actual posted speed limit signs
- Never rely solely on this app for speed limit information
- Use the app as a supplementary tool only
- Ensure safe driving practices regardless of what the app displays

**BY USING THIS APP, YOU ACKNOWLEDGE AND AGREE THAT:**
- The app is provided "as is" without warranties
- The developers are not liable for any traffic violations, accidents, or damages
- You are solely responsible for your driving behavior
- Speed limit and speed data may be inaccurate

---

## Children's Privacy

SpeedWise does not collect any personal information from anyone, including children under 13. Since no data is collected, there is no children's data to protect — the app functions entirely on-device.

---

## Your Rights and Control

You have complete control over the App:
- **Revoke Permissions:** You can revoke any permission at any time through your device settings. Some features may not function without required permissions.
- **Delete Data:** Uninstalling the app removes all locally stored data including trip history and preferences.
- **Disable Features:** You can disable specific features (speed limits, Bluetooth auto-launch, etc.) at any time within the app settings.

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by updating the "Last Updated" date at the top of this policy. You are advised to review this Privacy Policy periodically for any changes.

---

## Contact Us

If you have any questions or concerns about this Privacy Policy or our privacy practices, please contact us at:

**Email:** uaua.ltd+apps@gmail.com

**Developer:** UAUA Apps

---

## Summary

| Data Type | Collected? | Stored on Our Servers? | Shared with Third Parties? |
|-----------|------------|------------------------|----------------------------|
| Location/GPS | No | No | No* |
| Trip History | No | No | No |
| Speed Data | No | No | No |
| Personal Information | No | No | No |
| Usage Analytics | No | No | No |
| Advertising Data | No | No | No |
| Bluetooth Info | No | No | No |

*Geographic coordinates only are sent to OpenStreetMap for speed limit queries — no personal identifiers.

---

**Your speed data is your business. Your data stays on your device.**

**SpeedWise — Monitor your speed privately.**
