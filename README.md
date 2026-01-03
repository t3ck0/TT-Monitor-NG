# TT Monitor (Modernized Version)

![Android Version](https://img.shields.io/badge/Android-16%20Ready-green.svg)
![SDK](https://img.shields.io/badge/SDK-24+-blue.svg)
![Version](https://img.shields.io/badge/Version-1.01.014-orange.svg)

Dieses Repository bietet eine modernisierte Version der **TT Monitor App** (Original von NearbyExpress Tech). Da die ursprüngliche App auf aktuellen Android-Systemen nicht mehr unterstützt wird, wurde dieser Build dekompiliert, auf ein neues SDK gehoben und für moderne Hardware optimiert.

> ### ⚠️ Wichtiger Hinweis zur Installation
> Beim ersten Start kann die Meldung erscheinen, dass die App für eine **ältere Android-Version entwickelt wurde**. 
> 
> **Hintergrund:** Dies liegt an verbleibenden Legacy-Referenzen im ursprünglichen Code-Gerüst. Die App selbst wurde bereits auf SDK 24+ aktualisiert und für Android 16 optimiert. Diese Meldung wird in zukünftigen Refactoring-Updates entfernt. Die App ist sicher und voll funktionsfähig.

## 🚀 Highlights
* **Zukunftssicher:** Kompiliert mit SDK 24+, getestet und lauffähig bis **Android 16**.
* **Hardware-Erhalt:** Reaktiviert Bluetooth-Körperwaagen auf aktueller Hardware.
* **Unterstützte Modelle:** Optimiert für Geräte wie die **TaoTronics TT-MX001** und baugleiche Modelle von NearbyExpress.

## 🛠 Build-Informationen & Tools
Für maximale Transparenz wurde der folgende Stack verwendet:
* **Decompiling & Build:** [Apktool](https://github.com/iBotPeaches/Apktool)
* **Interface & Signatur:** [APKTool GUI v3.3.2.1](https://github.com/AndnixSH/APKToolGUI) (by AndnixSH)
* **Basis:** Original Legacy APK von NearbyExpress Tech.

## 📱 Features
* Drahtlose Datenübertragung via Bluetooth.
* Automatisches Tracking von Körperwerten (Gewicht, BMI, etc.).
* Historische Auswertung und Fortschrittsanzeige.

## 📥 Installation
1. Lade die `TT_Monitor_v1.01.014.apk` aus dem [Releases](../../releases) Bereich herunter.
2. Aktiviere "Installation aus unbekannten Quellen" in deinen Android-Einstellungen.
3. Starte die App, gewähre die Bluetooth-Berechtigungen (unter Android 16 ggf. "Geräte in der Nähe") und verbinde deine Waage.

---
*Disclaimer: Dies ist ein unabhängiges Community-Projekt zur Erhaltung der Hardware-Kompatibilität. Alle Markenrechte liegen bei den ursprünglichen Eigentümern (NearbyExpress Tech / TaoTronics).*
