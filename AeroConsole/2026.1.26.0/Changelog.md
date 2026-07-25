# AERO Console - 2026.1.26.0

## Changes

- [**Verge Remote**] Added persistent diagnostic logging to help support teams investigate connection and drone synchronization problems

## Bug Fixes

- [**Verge Remote**] Improved the reliability of the virtual remote pilot connection by automatically recovering from failed registration and interrupted network connections
- [**Verge Remote**] Fixed connected drones sometimes not appearing when Verge Remote was enabled after the drones had already connected
- [**Verge Remote**] Fixed a drone with unavailable position telemetry preventing other drones from updating in the remote pilot interface
- [**Network**] Fixed a failure in another network interface preventing Verge Remote from updating
