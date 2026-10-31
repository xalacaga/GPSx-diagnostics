# GPSx diagnostics

Public test reports sent by [GPSx](https://github.com/xalacaga/GPSx) from a
BenQ GP520 (Google TV, Android 11), mostly over Wi-Fi.

Each report is an **issue labelled `report`**, created from the phone by
scanning the QR code GPSx shows in Diagnostics (no token on the TV). The body is
a compact `gpsx-stream-test/1` summary: app version and source revision, device
and Android version, requested video profile and codec, network class with Wi-Fi
band/link speed/RSSI, start/duration/end reason, p50/p95/p99 statistics after a
5 s warm-up, audio API and counters, and up to 30 samples
`t fps mbps rtt loss lost audio`.

Reports never contain SSID, BSSID, IP addresses, console names, registration
keys or PSN tokens. `DEVICE` marks the GP520, `EMULATOR` the Android emulator.

---

# Diagnostics GPSx

Rapports de test publics envoyés par GPSx depuis un BenQ GP520, surtout en Wi-Fi.
Chaque rapport est un **ticket avec l'étiquette `report`**, créé depuis le
téléphone en scannant le QR code affiché dans Diagnostics (aucun jeton sur la TV),
sans SSID, BSSID, adresse IP, nom de console, clé d'enregistrement ni jeton PSN.
