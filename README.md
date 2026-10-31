# GPSx diagnostics

Public test reports uploaded by [GPSx](https://github.com/xalacaga/GPSx) from a
BenQ GP520 (Google TV, Android 11), mostly over Wi-Fi.

Each file under `results/YYYY/MM/` is one streamed session in the
`gpsx-stream-test/1` JSON format: app version and source revision, device model
and Android version, requested video profile and codec, network class with
Wi-Fi band/link speed/RSSI, start/end and end reason, p50/p95/p99 summaries after
a 5 s warm-up, and one sample per second
`[t, fps, bitrateMbps, rttMs, packetLoss, framesLost, width, height]`.

Reports never contain SSID, BSSID, IP addresses, console names, registration
keys or PSN tokens. `evidenceClass` is `DEVICE` on the GP520 and `EMULATOR` on
the Android emulator.

---

# Diagnostics GPSx

Rapports de test publics envoyés par GPSx depuis un BenQ GP520, surtout en
Wi-Fi. Un fichier par session dans `results/AAAA/MM/`, au format
`gpsx-stream-test/1`, sans SSID, BSSID, adresse IP, nom de console, clé
d'enregistrement ni jeton PSN.
