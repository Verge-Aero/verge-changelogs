# Maestro - v1.5.0

## Features

- [Hivemind] adds branching cue support, enabling smart RTH
- [Hivemind] adds forceable disarm support
- [Hivemind] adds LoRa RSSI report back to console
- [Hivemind] adds prediction framework for smart geofence
- [Hivemind] adds 'JobInfo' for processes like upload and firmware update
- [Hivemind] adds support for preshow configuration
- [Hivemind] adds predictive geofence support
- [Hivemind] adds compact compressed stream support
- [Hivemind] adds data management module
- [Hivemind] adds hivemind parameter support
- [Hivemind] turns lights on automatically on the ground after failsafe disarm

## Enhancements

- [Hivemind] updates show file management to greatly improve upload performance
- [Hivemind] moves hivemind show choreography to separate library
- [Maestro] adds additional continuous integration tests and workflows
- [Hivemind] automatically ends running show after disarming from failsafe
- [Hivemind] updates logging interfaces
- [Hivemind] improves post show tests
- [Hivemind] improves logging messages system wide
- [Hivemind] automatically configures autopilot baud rate
- [Hivemind] adds pyro trigger position check on Trigger
- [Hivemind] disables 'green light' on post show
- [Hivemind] disables show lights on failsafe
- [PX4] relaxs GNSS pos/vel speed accuracy requirements
- [PX4] improves gps timeout failure
- [PX4] increases default down velocity limit

## Bug Fixes

- [Hivemind] fixes various potential null reference exceptions
- [Hivemind] Increased X1 pyro post firing settle time
- [Hivemind] Adds pyro module self-test verification
- [Hivemind] Fixes Proximity Mode initialization
- [PX4] fixes false positive 'no sdcard' error
- [Hivemind] fixes no takeoff motors spinning continuously
- [PX4] fixes Here4 hardware issues

## Changes

- [Hivemind] operates on archive for shows instead of individual slot files

## Known Issues



