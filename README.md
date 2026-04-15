Privacy Policy — AP-Scout Pro
Last updated: April 9, 2026
Developer: QANDIX
Contact: support@qandix.com

1. INFORMATION WE COLLECT

AP-Scout Pro does NOT collect, transmit, or store any personal data
on external servers. All data processing occurs entirely on your device.

The following permissions are used locally only:

• Location (ACCESS_FINE_LOCATION, ACCESS_COARSE_LOCATION):
  Required by Android 14+ to retrieve Wi-Fi scan results including
  SSID and BSSID values. Location data is used only in-memory to
  display nearby Access Points and is never stored or transmitted.

• Nearby Wi-Fi Devices (NEARBY_WIFI_DEVICES):
  Required to scan for Wi-Fi Access Points on Android 13+.

• Internet (INTERNET):
  Used only by the Utility (Network Tools) feature to perform
  on-demand network diagnostics (Ping, DNS, HTTP Check, etc.)
  at the user's explicit request. No background connections are made.

• Wi-Fi State (ACCESS_WIFI_STATE, CHANGE_WIFI_STATE):
  Used to initiate Wi-Fi scans and read scan results. No data
  is transmitted externally.

2. DATA STORAGE & ENCRYPTION

• The AP Database is encrypted on-device using AES-256-GCM with
  PBKDF2 key derivation (600,000 iterations). The encryption key
  is derived from a user-provided passphrase and is held only in
  volatile memory — never stored on disk.
• Survey data and scan snapshots are stored locally in the app's
  private cache directory on your device.
• Exported files (CSV, Excel) can be optionally encrypted with
  AES-256 before sharing. Passwords are never saved.
• No cloud backup, no sync, no remote storage.

3. THIRD-PARTY SERVICES

AP-Scout Pro does NOT integrate:
• Analytics SDKs (no Firebase Analytics, no Crashlytics, no Mixpanel)
• Advertising networks (no AdMob, no ads of any kind)
• Social media SDKs
• Any external API services that receive user data

The only third-party code used is open-source libraries (Apache POI,
zip4j, Jetpack Compose, AndroidX) running entirely on-device.

4. NETWORK TOOLS — USER CONSENT

The Utility (Network Tools) feature requires explicit user consent
before first use. All network operations are initiated manually by
the user and directed only at hosts/addresses the user specifies.
No automated or background network requests are made.

5. CHILDREN'S PRIVACY

AP-Scout Pro is a professional enterprise tool not directed at
children under 13. We do not knowingly collect data from children.

6. CHANGES TO THIS POLICY

We may update this Privacy Policy from time to time. Changes will
be reflected in the "Last updated" date above. Continued use of the
app after changes constitutes acceptance of the updated policy.

7. CONTACT

For privacy questions or requests, contact:
support@qandix.com
