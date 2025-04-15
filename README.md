# O2-SpeedTuning

**Optimierte Netzwerk-Einstellungen für O2-Mobilfunk (iOS/macOS)**

---

## **Inhalt des Pakets**

- **IPv6-Deaktivierung** (`.mobileconfig`)  
  → Blockiert IPv6 vollständig systemweit  
  → Verhindert IPv6-Leaks bei VPN-Nutzung

- **WireGuard VPN-Konfiguration** (für O2 optimiert)  
  → Fokus: **Speed**, **Stabilität**, **IPv4-only**  
  → Cloudflare DNS über VPN erzwungen

- **Cloudflare DNS-Zwang** (`1.1.1.1`)  
  → Werbefrei, schnell, kein Tracking  
  → Schutz vor DNS-Leaks ohne App-Installation

---

## **Download**

[► O2_SpeedTuning.zip herunterladen](https://github.com/...)

---

## **Installation & Hinweise**

- **Kompatibel mit:** iOS 16–17+, macOS 13–14+
- **Einrichtungsschritte:** enthalten in `Anleitung.pdf` im ZIP
- **Voraussetzung:**  
  - iPhone/iPad/Mac mit aktueller Version  
  - „Dateien“-App und ggf. WireGuard-App (kostenlos)

- **Nutzungshinweis:**  
  → Nur für **private**, nicht-kommerzielle Verwendung  
  → Keine Weitergabe ohne Anpassung/Quellenverweis

---

## **Empfohlene Nutzung**

- **VPN dauerhaft aktivieren** (Passepartout oder iOS-Kurzbefehl)
- **iPhone im Mobilfunknetz verwenden (nicht WLAN)**  
  → Optimierung wirkt nur bei mobiler Datenverbindung

---

## **Optional (nicht enthalten)**

- **VPN-Auto-Start Shortcut** bei mobilen Daten  
- **Supervised Mode** für Profil-Zwang auf iOS  
- **Speedtest-Automation** (Shortcut oder Siri-Kurzbefehl)

---

## **Geplant (coming soon)**

- [ ] Optionale AdGuard DNS  
- [ ] SpeedBoost für Android  
- [ ] APN-Profil für manuelle Bandwahl (Testphase)