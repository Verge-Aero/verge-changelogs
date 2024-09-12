# AERO Studio - 2024.2.0.0

## Features

- [**Splines**] When partial spline is selected, slotting start t and end t can now be animated
- [**Drone Control**] Payload target system can now be exported as a yaw stream in vbakes. Drones can be pointed in specific directions
- [**Pyro Module**] Added pyro module trigger support. Exports now include commands to trigger the Verge X1 Pyro Module
- [**Pyro**] Added ability to set individual mount directions for pyro payloads
- [**Payload Targets**] Directionality of pyro payloads are now reflected in the editor view as color-coded arrows
- [**Modifiers**] Added "Melt" modifier

## Improvements

- [**UI**] Updated to use new UI layouts
- [**Object Arrays**] Arrays now cap maximum available slots for formation sequences and formation groups

## Bug Fixes

- [**Safety Zone**] Fixes realtime safety zone not updating until timeline is adjusted
- [**Scatter Field**] Fixed crash that could occur when applying modifiers to a scatter field
- [**Choreography Event**] Fixed crash that could occur when cleaning up a track event
