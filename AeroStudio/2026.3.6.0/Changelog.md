# AERO Studio - 2026.3.6.0

## Improvements

- [**Show Environment**] Show GPS coordinates now retain the last-used latitude and longitude and fall back to a default non-zero location when no saved coordinate is available
- [**Map Elevation**] Loading a show now queues automatic map elevation fitting so the GPS anchor altitude can be refreshed after tiles and launchpad location are available
- [**Object Picker**] Expanded object pickers now size against the scene view and use the configured scroll view layout to avoid clipping below the scene view
- [**Track Lighting**] Formation sequence track lighting lanes now appear in the timeline when track lighting is enabled
- [**Lighting Effects**] Spatial Gradient now maps X/Y/Z and radial gradients over the current spatial bounds instead of repeating raw coordinate values

## Changes

- [**Lighting Effects**] Mirror fade-in is disabled by default for lighting effect layers, including older assets upgraded into the current format
- [**Track Lighting**] Removed the obsolete Track Lighting Blackout event from drone channel workflows
- [**Track Lighting**] Cleaned up fade controls in lighting effect inspectors

## Bug Fixes

- [**Scene View Input**] Fixed paint tools intercepting scroll input over the timeline or hierarchy and unintentionally zooming the scene view
- [**Timeline**] Fixed wheel input above channel lanes continuing to scroll channels after the timeline had been vertically scrolled
- [**Timeline**] Fixed cross-channel event drags trying to shift linked or selected events into adjacent lanes when the pointer never left the active event lane
- [**Timeline**] Fixed formation sequence crossfade overlay channels not appearing in the timeline for customization
- [**Object Picker**] Fixed Object Picker scroll view layout so expanded object lists stay within the scene view
- [**Yaw Payloads**] Fixed issue where compressed yaw streams caused incorrect rotation
