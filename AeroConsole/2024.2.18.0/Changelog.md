# AERO Console - 2024.2.18.0

## Features

- [*BMS*] Added advanced battery info for X7s
- [*BMS*] Added button to turn off X7s remotely
- [*Device Grid*] Added indicator that turns white when a drone receives an update
  - Can be disabled via the top panel
- [*Device Grid*] Added text filter to simplify searching for a drone
  - Text filter hotkey is bound to Ctrl + F
- [*Device Grid*] Added filter for hiding X1/X7
- [*Logging*] Added new, automated data capture that records all important information about show performances
  - Data can be uploaded to the Aero Portal and reviewed post-mortem
  - Issues are automatically reported
- [*Network*] Added latency and version readouts for Maestro server
- [*Network*] Console now actively reports the state/s of the AT86 and LoRa radios
- [*Network*] Added debug functionality for network gateways
- [*Network*] New Network Configuration Wizard allows users to modify the radio channels being used on the network gateways from the console
- [*Network*] Added ability to force drones to reconnect to the server
- [*Network*] Added ability to force one or multiple drones to be booted from the server
- [*Shows*] Cloud-rendered shows can now be accessed, downloaded, and loaded from inside of the console
- [*Slotting*] New smart-slotting algorithm massively improves slot selection
  - Added ability to select "Static Mode" for drone slotting. Gives users ability to slot or unslot drones independently
  - Manually batch slot drones immediately, bypassing the need to wait for the vehicles to update themselves
  - Launchpad dimensions and density are displayed in the slotting panel
- [*Testing*] Added UI for triggering motor tests on one or more drones
- [*UI*] System clock is now displayed in the bottom-right
- [*Verge Remote V2*] Added new system for remotely monitoring and operating the console
  - Verge Remote can be accessed from a mobile phone or web browser via the Aero Portal
  - Drone light modes can be modified, can be reset, and calibrated remotely
  - A full view of the launchpad and slotting states can be seen in a 3D map
- [*VPKG*] Verge software packages can now update the maestro server and network gateways
- [*VPKG*] Verge software packages can now be downloaded and installed from inside of the console

## Improvements

- [*Light Modes*] Light modes can now be selected and applied with a single action in a flat button panel rather than a dropdown
- [*Network*] When a single drone is selected, updates are prioritized for that device
- [*Performance*] No longer draws 3D view when in grid view
- [*UI*] Total rework of drone inspector
- [*UI*] Layout improvements
- [*UI*] Anchor adjustment UI now has square scaling to improve visibility
- [*UI*] Anchor adjustment UI now places adjustment UI next to adjustment graph
- [*UI*] Filter now shows device types rather than object resources
- [*UI*] Added inspector for when multiple drones are selected
- [*UI*] Added option to quickly switch to manual launch trigger
- [*UI*] Collapses inspector view to provide more device grid view space
- [*UI*] Visual improvements to command bar

## Bug Fixes

- [*Scene View*] Drones and slotting info are now drawn in showtime mode
- [*Device Grid*] Filters default to show all info when drones first connect
