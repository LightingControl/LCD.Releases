# LCD driver releases for Crestron

[![Latest drop](https://img.shields.io/github/v/release/LightingControl/LCD.Releases?sort=date&label=latest%20drop&style=for-the-badge&logo=github&color=0969da)](https://github.com/LightingControl/LCD.Releases/releases/latest)
[![Driver status](https://img.shields.io/badge/driver%20status-latest%20releases-0969da?style=for-the-badge)](https://lightingcontrol.github.io/LCD.DriverStatus/)
[![Service status](https://img.shields.io/badge/service%20status-uptime%20page-0969da?style=for-the-badge)](https://status.lcd.network/)
[![Docs](https://img.shields.io/badge/docs-lcd.network-0969da?style=for-the-badge)](https://lcd.network/)

Each release here is one drop sent to the Crestron drivers team: a single `YYYY-MM-DD.zip` holding every
driver `.pkg` in that drop, flat at the root, ready for one upload to the Crestron driver catalogue.

Each release also carries `manifest.json` (driver, SKU, version, source release and sha256 of each package)
and `notes.md` (each driver's release notes). The packages themselves come unchanged from each driver
repository's own GitHub release.

## Drivers

Versions below are read live from each driver's published release data.

| Driver | Latest release |
| --- | --- |
| [2N Lock](https://lightingcontrol.github.io/Lcd.2N.Lock/) | ![2N Lock latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLcd.2N.Lock%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |
| [2N Doorstation](https://lightingcontrol.github.io/Lcd.2N.DoorStation/) | ![2N Doorstation latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLcd.2N.DoorStation%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |
| [Sonos Chime](https://lightingcontrol.github.io/Lcd.Sonos.Chime/) | ![Sonos Chime latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLcd.Sonos.Chime%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |
| [UI Dynamic](https://lightingcontrol.github.io/Lcd.UiDynamic/) | ![UI Dynamic latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLcd.UiDynamic%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |
| [Ajax Security](https://lightingcontrol.github.io/LCD.Chome.Ajax.Security/) | ![Ajax Security latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLCD.Chome.Ajax.Security%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |
| [Vacation Lighting Scheduler (HomeAway)](https://lightingcontrol.github.io/Lcd.CHHOMEAWAY/) | ![Vacation Lighting Scheduler (HomeAway) latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLcd.CHHOMEAWAY%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |
| [Alarm Clock](https://lightingcontrol.github.io/Lcd.AlarmClock/) | ![Alarm Clock latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLcd.AlarmClock%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |
| [LCD Dashboard](https://lightingcontrol.github.io/Lcd.Dashboard/) | ![LCD Dashboard latest release](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flightingcontrol.github.io%2FLcd.Dashboard%2FProductData%2Fproduct.json&query=%24.LatestVersion&label=release&color=2ea44f&style=flat-square) |

## Links

- [All drops](https://github.com/LightingControl/LCD.Releases/releases)
- [Driver status](https://lightingcontrol.github.io/LCD.DriverStatus/): the latest release of each driver and whether Crestron lists it yet
- [V1 driver status](https://lightingcontrol.github.io/LCD.DriverStatus/legacy-drivers.html): the older driver range, with downloads
- [Service status](https://status.lcd.network/): uptime of the LCD online services
- [Documentation](https://lcd.network/)
- [Driver downloads and side-loading](https://lcd.network/driver-downloads/)
- [Crestron driver catalogue](https://drivers.crestron.io/)
- [LCD website](https://www.lightingcontrol.co.uk/)

Questions about a drop: [drivers@lightingcontrol.co.uk](mailto:drivers@lightingcontrol.co.uk).
