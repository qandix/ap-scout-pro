Privacy Policy — AP-Scout Pro
Package: com.qandix.apscout
Developer: Qandix
Contact: support@qandix.com
Last updated: 2026-06-27


AP-Scout Pro ("the App") is developed by Qandix. This Privacy Policy explains
what information the App accesses, how it is used, and how it is protected.


1. INFORMATION WE COLLECT

The App accesses the following data solely on your device:

• Wi-Fi scan data (BSSID, SSID, RSSI, channel, band) — used for Scan, Track,
  Survey, and Roaming Analysis. Stored locally on device only.
• GPS / location coordinates — used to geotag signal readings in Site Survey.
  Stored locally on device only.
• Sensor data (accelerometer, magnetometer, gyroscope) — used for the Tracking
  compass heading. Not stored.
• Floor plan images — the floor-plan background you upload in Survey (paid).
  Stored locally on device only.
• Survey session data — used for export and review. Stored locally on device only.
• AP Database (CSV import) — used to display hostnames instead of BSSIDs.
  Stored locally on device only.
• Network Tools activity — on-demand diagnostics (Ping, DNS, Traceroute, Port Check,
  HTTP Check, TLS Inspector, NTP, ARP Table, Network Overview, LAN Discovery) directed
  at hosts/networks you specify. Not stored; not transmitted off-device.

We do not collect, transmit, or store any personal data on external servers, with one
optional exception you control: the Network Overview "Public IP" lookup (off by default)
contacts ipinfo.io only when you tap it — see THIRD-PARTY SERVICES below.

Network Tools: these require explicit one-time consent before first use. Every operation
is initiated manually by you and is directed only at the hosts/addresses/networks you
specify; the App makes no automated or background network requests. Results and any read
of the local ARP neighbor cache are shown on-device and are neither stored nor transmitted
off-device.


2. THIRD-PARTY SERVICES

The App integrates the following Google services, each governed by Google's
Privacy Policy (https://policies.google.com/privacy):

• Google Play Billing — Survey paid-features monthly subscription payment processing.
• Google Play Integrity API — app license verification.

We do not receive, store, or process any payment card information. All billing is
handled exclusively by Google Play.

Public IP lookup (optional, off by default): when you tap "Look up Public IP" in
Network Overview, the App makes a single HTTPS request to ipinfo.io (fallback
api.ipify.org) to show your public IP address, ISP and approximate location. Those
services necessarily see your IP address, governed by their own privacy policies
(https://ipinfo.io/privacy-policy). This is the only feature that contacts a
non-Google external service, it never runs on its own, and no other personal data
is sent.


3. PERMISSIONS USED

• ACCESS_WIFI_STATE — read Wi-Fi scan results.
• CHANGE_WIFI_STATE — trigger Wi-Fi scans.
• ACCESS_FINE_LOCATION — required by Android for Wi-Fi scanning (API 34+) and GPS
  for Site Survey.
• ACCESS_COARSE_LOCATION — required by Android for Wi-Fi scanning.
• NEARBY_WIFI_DEVICES — required on Android 13+ for Wi-Fi scanning.

Location data is used only within the App and is never transmitted externally.


4. DATA STORAGE AND SECURITY

• All app data is stored in the app's private internal storage (filesDir / cacheDir).
• Data is not accessible to other apps.
• No cloud sync, no remote backup.
• Exports (CSV / Excel / ZIP, including the bulk Survey export that mirrors your
  Project > Site > Building > Floor tree) are written on your device and leave it
  only when you share them via the target you choose. Excel and ZIP exports can be
  password-protected (AES-256); passwords are never saved.
• Uninstalling the App removes all stored data.


5. SUBSCRIPTION DATA

The Survey paid features (floor-plan background, on-map point placement with
pinch-to-zoom, AP Check Points, point aliases, and up to 5000 points) require a
monthly subscription through Google Play. We do not collect or store payment card
information, billing address, or purchase history beyond what Google Play provides
to verify subscription status.


6. CHILDREN'S PRIVACY

This App is designed for professional network engineers and is not intended for
use by children under 13.


7. CHANGES TO THIS POLICY

We may update this Privacy Policy from time to time. Changes will be posted at the
same URL with an updated "Last updated" date.


8. CONTACT

Email: support@qandix.com


Last updated: 2026-06-27 | AP-Scout Pro v6.0.7
