### UAV Link List

A list of open-source projects for radio links with UAVs.

## Multipurpose Link
- [DroneBridge](https://github.com/DroneBridge/DroneBridge)
  - "One link to rule them all"
    - Telemetry: Bidirectional MAVLink, LTM depreciated
    - RC: 12 channel. Current version (0.7) has high latency.
    - Video: up to 1080p, OSD, 110ms latency
  - Uses wifibroadcast
  - Range 0.3 - 14+ km (0.5-2km typical)
  - Companion Android app
  - Hardware:
    - RPi to RPi
    - Single ESP32 (no video). Web interface.
- [OpenHD](https://github.com/OpenHD/Open.HD)
  - Multifunction link
    - Telemetry: Bidirectional MAVLink (uplink dependent on FC support)
    - RC: Supports MAVLink or MSP/SUMD/IBUS/XBUS
    - Video: 720p/60 to 1080p/30 (max 12Mb/s), 125ms typical
  - RPi to RPi
  - Multiband, diversity support

## Proximity Beacon

- [iNavRadar](https://github.com/mistyk/inavradar-ESP32)
  - LoRa + ESP32 location broadcast/recieving
  - OSD overlay
  - INAV only
- [SoftRF](https://github.com/lyusupov/SoftRF)
  - Bridges proximity radio network to WiFi
    - One or more of FLARM, OGN, PilotAware, Skytraxx
  - Can feed to an ADS-B compatible flight controller
    - Project not primarially targeting UAVs
  


## Generic Serial Link
- [ESP32 Serial Bridge](https://github.com/AlphaLima/ESP32-Serial-Bridge)
  - TCP over WiFi to all 3 serials.
- [MavESP8266](https://github.com/dogmaphobic/mavesp8266)
    - Serial link over WiFi with single ESP8266.
    - Web interface.
    - Last commit May 2020.

## Legacy Projects
  - [openLRSng](https://github.com/openLRSng/openLRSng)
    - Last commit Nov 2018. Recommended hardware is domain squatter.
  
