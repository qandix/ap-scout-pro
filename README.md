# Privacy Policy — AP-Scout Pro
**Package:** `com.qandix.apscout`
**Developer:** Qandix
**Contact:** support@qandix.com
**Last updated:** 2026-08-01

---

## Privacy Policy

**AP-Scout Pro** ("the App") is developed by Qandix. This Privacy Policy explains what information the App accesses, how it is used, and how it is protected.

---

### 1. Information We Collect

The App accesses the following data **solely on your device**:

| Data | Purpose | Stored |
|------|---------|--------|
| Wi-Fi scan data (BSSID, SSID, RSSI, channel, band) | Scan, Track, Survey, Roaming Analysis | Locally on device only |
| Beacon metadata broadcast by APs (advertised AP name, vendor fields, and — where an AP advertises it — the AP's own GPS coordinates) | Decoded passively on-device from frames APs already broadcast; shown as the 📡 AP name and included in the Beacon sheet of exports (incl. a raw frame hex column) | In-memory only; written out only into export files you create |
| GPS / location coordinates | Site Survey — geotag signal readings | Locally on device only |
| Sensor data (accelerometer, magnetometer, gyroscope) | Tracking compass heading | Not stored |
| Floor plan images | Survey (paid) — floor-plan background uploaded by user | Locally on device only |
| Survey session data | Export and review | Locally on device only |
| AP Database (CSV import) | Display hostnames instead of BSSIDs | Locally on device only |
| Network Tools activity | On-demand diagnostics (Ping, DNS, Traceroute, Port Check, HTTP Check, TLS Inspector, TCP Throughput, Latency Trend, Subnet Calculator, Wake-on-LAN, NTP, ARP Table, Network Overview, LAN Discovery) to hosts/networks you specify | Not stored; not transmitted off-device |
| Diagnostic activity logs (app events only — no personal data) | Field diagnostics via the Logs menu — records the App's own activity (a built-in Logcat replacement). Recording is **opt-in and OFF by default**: nothing is recorded until you turn on the switch in the Logs menu | Locally on device only, encrypted (AES-256-GCM); you can view, export, or delete them anytime via the Logs menu |

**We do not collect, transmit, or store any personal data on external servers, with one optional exception you control:** the Network Overview "Public IP" lookup (off by default) contacts ipinfo.io only when you tap it — see *Third-Party Services* below.

**Network Tools.** The Network Tools require explicit one-time consent before first use. Every operation is initiated manually by you and is directed only at the hosts/addresses/networks you specify; the App makes no automated or background network requests. Results and any read of the local ARP neighbor cache are shown on-device and are neither stored nor transmitted off-device.

---

### 2. Third-Party Services

The App integrates the following Google services, each governed by Google's Privacy Policy ([policies.google.com/privacy](https://policies.google.com/privacy)):

| Service | Purpose |
|---------|---------|
| **Google Play Billing** | Survey paid-features monthly subscription payment processing |
| **Google Play Integrity API** | App license verification |

We do not receive, store, or process any payment card information. All billing is handled exclusively by Google Play.

**Public IP lookup (optional, off by default).** When you tap "Look up Public IP" in Network Overview, the App makes a single HTTPS request to **ipinfo.io** (fallback **api.ipify.org**) to show your public IP address, ISP and approximate location. Those services necessarily see your IP address, governed by their own privacy policies ([ipinfo.io/privacy-policy](https://ipinfo.io/privacy-policy)). This is the only feature that contacts a non-Google external service, it never runs on its own, and no other personal data is sent.

---

### 3. Permissions Used

| Permission | Why |
|------------|-----|
| `ACCESS_WIFI_STATE` | Read Wi-Fi scan results |
| `CHANGE_WIFI_STATE` | Trigger Wi-Fi scans |
| `ACCESS_FINE_LOCATION` | Required by Android for Wi-Fi scanning (API 34+) and GPS for Site Survey |
| `ACCESS_COARSE_LOCATION` | Required by Android for Wi-Fi scanning |
| `NEARBY_WIFI_DEVICES` | Required on Android 13+ for Wi-Fi scanning |

Location data is used only within the App and is never transmitted externally.

---

### 4. Data Storage and Security

- All app data is stored in the app's **private internal storage** (`filesDir` / `cacheDir`)
- Data is not accessible to other apps
- No cloud sync, no remote backup
- Exports (CSV / Excel / ZIP, including the bulk Survey export that mirrors your Project ▸ Site ▸ Building ▸ Floor tree) are written on your device and leave it only when you share them via the target you choose. Excel and ZIP exports can be password-protected (AES-256); passwords are never saved.
- Diagnostic activity logs are recorded only after you opt in (the recording switch in the Logs menu is OFF by default) and are stored encrypted (AES-256-GCM) with a device-internal key held in the Android Keystore; they contain app events only (no personal data), never leave the device unless you export them, and can be exported as plain TXT or a password-protected AES-256 ZIP
- Uninstalling the App removes all stored data

---

### 5. Subscription Data

The Survey paid features (floor-plan background, on-map point placement with pinch-to-zoom, AP Check Points, point aliases, and up to 5000 points) require a monthly subscription through Google Play. We do not collect or store payment card information, billing address, or purchase history beyond what Google Play provides to verify subscription status.

---

### 6. Children's Privacy

This App is designed for professional network engineers and is **not intended for use by children under 13**.

---

### 7. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted at the same URL with an updated "Last updated" date.

---

### 8. Contact

**Email:** support@qandix.com

---

*Last updated: 2026-08-01 | AP-Scout Pro v6.0.32*
