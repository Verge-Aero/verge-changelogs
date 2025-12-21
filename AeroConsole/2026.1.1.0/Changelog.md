# AERO Console - 2026.1.1.0

## Features
- [**Base Station**] Added support for new base station
    - Added support for base station timecode
    - Added support for multi-RTK base stations
    - Added feedback for base station UPS status
        - Messages now appear when base station is on backup power, is missing a battery, and more
- [**Satellite Info**] Added new satellite info inspector that allows RTCM data to be recorded and inspected
- [**GPS Health**] Added new GPS Health view
  - Added heatmap that shows GPS accuracy in the 3D view
  - Added 3D satellite ray view
  - Added panel that shows the current satellites for any selected device that has a GPS module
- [**Radio Health**] Added new radio health view
  - Added histograms that show a summary of the radio quality of the fleet
  - Added heatmap that shows the quality of receive signal for LoRa or AT86 radio
- [**Telemetry**] A new telemetry protocol has been implemented that significantly improves the quality and content of drone telemetry
  - Added LoRa RSSI
  - Added radio channel info
  - Added wind estimates
  - Added spatial error
  - Added latency info
- [**Showtime**] Added (skippable) pre-show -> Showtime transition step that scans and addresses any remaining issues before switching mode
  - Ensures that no two drones are targeting the same slot
## Enhancements
- [**Timecode**] Added new graph analysis tools to more easily identify timecode issues
- [**GPS Anchor**] Altitude resolution has been re-written to be more accurate and easier to use
- [**VPKG**] Firmware package picker UI has been greatly improved
- [**Telemetry**] In-flight telemetry rate has been raised by a factor of 5 by default, bringing it in line with the ground report rate
- [**Telemetry**] A selected drone will now provide increased packet rate during showtime mode
- [**Device Grid**] Added sort-by voltage
- [**Device Grid**] Added ability to search by owner name in Ownership view
- [**Device Grid**] Only shows drones that have pyro module in the pyro view
- [**Pyro**] Significantly improves the reliability of manually disarming pyro in-flight
## Bug Fixes
- [**General**] Fixed ~20 second delay when shutting down the Console application. This would make it appear the application was freezing up.
- [**Network**] Fixed issue where gateways would connect and disconnect rapidly when initializing a connection
- [**Network**] Fixed rare crash that could occur when multiple threads were writing to the playerlog
