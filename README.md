# 🏠 My Home Assistant Blueprints Collection

This repository is a collection of my custom Blueprints for Home Assistant. Optimized for reliability and deep integration with **Synology**, **FritzBox**, and system monitoring.

## 🚀 Available Blueprints

| Blueprint Name | Quick Import | Description |
| :--- | :--- | :--- |
| **Job Complete Notifier** | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Cavekeeper/HomeAssistant/main/job_complete_notifier.yaml) | Notification when a device (e.g. washing machine) has finished its task. |
| **Synology Alarm Snapshot** | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Cavekeeper/HomeAssistant/main/syno_alarm_snapshot.yaml) | Snapshot notification for Surveillance Station alarms. |
| **Smart Light – Trigger** | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Cavekeeper/HomeAssistant/main/smartlight_trigger.yaml) | Stable motion-activated light automation. |
| **Smart Shading: ON** | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Cavekeeper/HomeAssistant/main/smart_rollershutter_shading_on.yaml) | Lowers roller shutters for shading based on solar conditions. |
| **Smart Shading: OFF** | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Cavekeeper/HomeAssistant/main/smart_rollershutter_shading_off.yaml) | Raises roller shutters when shading is no longer needed. |

---

## 🛠 Installation

1. **Click the "Import Blueprint" button** above for the desired automation.
2. Home Assistant will open a dialog to confirm the import.
3. Alternatively, copy the `raw` link of any `.yaml` file and paste it under **Settings > Automations > Blueprints > Import**.

<details>
<summary>⚖️ Legal & Technical Disclaimer (Click to expand)</summary>

## ⚠️ Disclaimer
**Use at your own risk.** * **Storage:** Ensure file paths exist on your system.
* **Hardware:** Optimized for Raspberry Pi and Synology DSM 7.x.
* **No Liability:** I am not responsible for data loss or hardware wear.
</details>

---

## 💾 System Context
* **Core:** Home Assistant on **Raspberry Pi**.
* **DB:** **MariaDB** on **Synology NAS** (SD card protection).
* **Network:** **FritzBox** integrated.

*Created with ❤️ for a smarter home.*