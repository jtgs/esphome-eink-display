# ESPHome E-ink Display

Configuration for Lilygo T5-4.7-S3 e-ink displays to integrate with ESPhome.

Built on https://github.com/nickolay/esphome-lilygo-t547plus and inspired by https://github.com/davidz-yt/eink-desk-display.

## Setup

1. Obtain font files and add them to `fonts/` directory
2. Set wifi credentials in `wifi-secrets.yaml` (use template file)
3. Set a password for API access to Home Assistant in `secrets.yaml` (use template file)
4. `esphome run <room>.yaml`
5. In Home Assistant, adopt new device using password you set in (3)
