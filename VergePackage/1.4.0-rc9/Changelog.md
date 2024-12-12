# Maestro - v1.4.0

## Features

- [Hivemind] adds 'version' application
- [Hivemind] adds F7 support back
- [Maestro] adds X7 support
- [Hivemind] adds long range compatibility support for both X7 and X1 via same radio
- [Hivemind] adds smart battery logging
- [PX4] adds drone and show metadata to log files
- [Maestro] supports X1 and X7 on the same kernel
- [MaestroServer] adds forced agent disconnect
- [PX4] adds support for Here4 F9P module
- [Maestro] support for Verge Aero pyrotechnics module
- [Hivemind] reports voltage and current to Console

## Enhancements

- [Ubloxgs] increases client lifetime to 1 day
- [Hivemind] updates UID to include full drone ID
- [Hivemind] optimizations for show unpacking
- [Hivemind] adds bail-out logic when a drone is poorly receiving file uploads
- [MaestroServer] removes initial file generation wait time
- [NuttX] updates NuttX kernel to v10.0
- [PX4] upgrades PX4 to v1.15 stable
- [Hivemind] improves temperature sensor driver
- [Hivemind] changes status light mode to reflect unhealthy, unslotted, or slotted
- [Hivemind] assigns random UID if no ID is provided
- [Hivemind] adds battery id and version number to device info
- [Hivemind] adds watchdog for commander so drone lands in case of lockup

## Bug Fixes

- [MaestroServer] fixes issue that limits file upload size
- [Hivemind] fixes show file cue test bug preventing light from becoming green
- [Hivemind] fixes various issues causing 'NONE' to be displayed
- [Hivemind] fixes parameter file hash reporting
- [Hivemind] fixes heading check bug where light turns green north and south
- [Hivemind] fixes lockup issue due to network running out of resources
- [Hivemind] fixes heading reporting issue
- [Hivemind] fixed CompactCompressed lighting streams
- [UBloxgs] fixes potential ubx overflow issue
- [Hivemind] fixed LoRa channel set on X7
- [PX4] fixes PWM issue on cubeorange bootloader

## Changes

- [Hivemind] LoRa header change for IEEE802.15.4 compatibility
- [Hivemind] updates LoRa bandwidth
- [Hivemind] adds 'Mag Failure' back to pre-show report
- [Hivemind] increases heading check threshold from 8 degrees to 20 degrees
- [Hivemind] does not delete network config on network timeout
- [Hivemind] adds battery information and autopilot flags to vehicle report

## Known Issues

- [PX4] False positive, transient 'invalid GPS' error


