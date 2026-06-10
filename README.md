# 🔔 Update-Benachrichtigung Blueprint

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FNoack1978%2Fha-update-notification%2Fblob%2Fmain%2Fupdate_notification.yaml)

Ein Home Assistant Blueprint, der automatisch über verfügbare Updates für Add-ons, Integrationen und Geräte-Firmware benachrichtigt – ohne dass neue Update-Entitäten manuell gepflegt werden müssen.

---

## ✨ Features

- **Vollautomatisch** – alle `update.*`-Entitäten werden dynamisch erfasst, neue Updates werden sofort erkannt
- **Ausschlussliste** – beliebige Update-Entitäten (z. B. HA Core, OS, Supervisor) können per UI ausgeschlossen werden
- **Multi-Device** – beliebig viele Mobilgeräte (Companion App) können benachrichtigt werden
- **Tägliche Erinnerung** – konfigurierbare Uhrzeit für eine morgendliche Zusammenfassung
- **Persistente Benachrichtigung** – optional zusätzlich in der HA-Oberfläche anzeigen
- **Auto-Dismiss** – Benachrichtigungen werden automatisch gelöscht, wenn alle Updates installiert sind

---

## ⚙️ Konfiguration

| Option | Beschreibung | Standard |
|---|---|---|
| **Zu benachrichtigende Geräte** | Geräte mit Companion App, die Push-Nachrichten erhalten | – |
| **Auszuschließende Entitäten** | Update-Entitäten, die ignoriert werden sollen | keine |
| **Tägliche Erinnerungszeit** | Uhrzeit für die tägliche Erinnerung | 09:00 |
| **Persistente Benachrichtigung** | Anzeige in der HA-Oberfläche | aktiviert |

---

## 🚀 Installation

Den Import-Button oben klicken oder diesen Link verwenden:

```
https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Noack1978/ha-update-notification/blob/main/update_notification.yaml
```

---

## 🔄 Updates

Bei Änderungen am Blueprint in HA unter **Einstellungen → Automatisierungen → Blueprints** auf die drei Punkte klicken und **„Neu laden"** wählen.

---

## 👤 Autor

[Noack1978](https://github.com/Noack1978)
