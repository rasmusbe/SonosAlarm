# Sonos Alarm

Custom component for Home Assistant to control your SONOS Alarm

**Features:**

- Switch your alarms on/off
- no configuration needed
- information about you alarms, like time, volume, etc in attributes


## Installation

**Install via HACS**

The custom component is available via [HACS](https://github.com/custom-components/hacs)

**Manual Install**

If you want to install the custom commponent manually, add the folder `sonos_alarm/` to `YOUR_CONFIG_DIR/custom_components/`.

## Configuration
**As Integration:**

Go to the `Integrations pane` on your Home Assistant instance and search for `Sonos Alarm`.

## Exposed entities

- `switch.sonos_alarm_[id of your alarm]` for each of your SONOS Alarms