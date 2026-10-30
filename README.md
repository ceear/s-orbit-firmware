# s-orbit firmware

Signed firmware updates for s-orbit, a Sonos rotary controller running on the Waveshare ESP32-S3 Knob (1.8″ round touch display).

This repository only holds releases. Each release contains:

- `knob.bin`: the signed application image. The device only accepts images signed with the project key.
- `manifest.json`: `{"version": "…", "url": "…"}`. The device reads it from `releases/latest/download/manifest.json`.

Updates are installed from the device itself (menu card “Firmware update”). As an alternative, open the setup portal, tap the version number and upload `knob.bin`.
