# AERO Studio - 2025.1.0

## Features

- [**Painting**] Added new paint tools UI panel
    - Added paint brush tool
    - Added paint bucket tool
    - Added color dropper tool
    - Provides a much faster interface for color manipulation

- [**Point Clouds**] Vertices can now be painted using the new paint tools

## Improvements

- [**Transitions**] Added ability to stagger join objects sequentially based on geometric order
- [**Geofence**] Geofence generation now layers all calculations on top of a ballistics model
- [**Palettes**] Last opened palette is now saved

## Bug Fixes

- [**Cursor**] Fixed long-standing issue where cursor colors would be faded on all platforms
- [**Cursor**] Fixed the size of some cursors on OSX
- [**Palettes**] Fixed issue where palette names were not being saved
- [**3D Tiles**] Fixed issue that would cause tile credits to overlay on top of UI elements and block their use
- [**Audio**] Fixed unsupported audio clips to cause issues on the timeline
- [**Gradients**] Fixed deleting keys not updating the UI properly
- [**Gradients**] Fixed leaving only one key causing replacement key to not be drawn
- [**Preview**] Fixed launchpad lighting being layered out of order for previews
