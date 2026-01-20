# Home Assistant Blueprints

A collection of Home Assistant blueprints for automation.

## Automatic OS Updates with Version Control

Automatically install minor and/or major updates of Home Assistant OS at a chosen time.

### Features
- Choose to install minor updates (17.0 → 17.1) and/or major updates (17.x → 18.0)
- Set custom update time
- Persistent notifications for skipped updates
- Works with any update entity

### Installation

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/filmgarage/Ha_blueprints/blob/main/system/update_os.yaml)

Or manually: **Settings** → **Automations & Scenes** → **Blueprints** → **Import Blueprint** and paste:
```
https://github.com/filmgarage/Ha_blueprints/blob/main/system/update_os.yaml
```

### Usage
After importing, create a new automation from this blueprint and configure:
- **Update Entity**: Default is `update.home_assistant_operating_system_update`
- **Update Time**: Default is 04:00:00
- **Install Minor Updates**: Default enabled
- **Install Major Updates**: Default disabled

## License
MIT
