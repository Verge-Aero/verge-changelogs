# AERO Studio - 2025.1.0

## Features

- [**Painting**] Added new paint tools UI panel
    - Added paint brush tool
    - Added paint bucket tool
    - Added color dropper tool
    - Provides a much faster interface for color manipulation

- [**Point Clouds**] Vertices can now be painted using the new paint tools

- [**Splines**] Overhauled and expanded spline tools
    - Added segment select tool
    - Added spline select tool
    - Added edit support for compound splines
    - Added "to compound spline" tool
    - Added smooth tool
    - Added straighten tool
    - Added subdivide tool
    - Added extrude tool
    - Added split tool
    - Added group/ungroup tools
    - Added duplicate tool
    - Added undo/redo for all tools
    - Undo/Redo now preserves spline selection
    - Bounds are recomputed in realtime when modifying spline control points

## Improvements

- [**Transitions**] Added ability to stagger join objects sequentially based on geometric order
- [**Geofence**] Geofence generation now layers all calculations on top of a ballistics model
- [**Palettes**] Last opened palette is now saved
- [**Undo/Redo**] Added buttons for undo/redo to the toolbar
- [**Undo/Redo**] Creation of scene objects can now be undone
- [**Startup**] Load previous show dialog now shows show file name and filesize
- [**Scene Hierarchy**] Hierarchy is no longer hidden when showing a blocking prompt
- [**Scene Hierarchy**] Deselecting a changed hierarchy entry will now keep any rename
- 
## Bug Fixes

- [**Cursor**] Fixed long-standing issue where cursor colors would be faded on all platforms
- [**Cursor**] Fixed the size of some cursors on OSX
- [**Palettes**] Fixed issue where palette names were not being saved
- [**3D Tiles**] Fixed issue that would cause tile credits to overlay on top of UI elements and block their use
- [**Audio**] Fixed unsupported audio clips to cause issues on the timeline
- [**Gradients**] Fixed deleting keys not updating the UI properly
- [**Gradients**] Fixed leaving only one key causing replacement key to not be drawn
- [**Preview**] Fixed launchpad lighting being layered out of order for previews
- [**Geofence**] Fixed issue where having a 1D geofence shape could cause a crash
- [**Pyro**] Fixed issue where comets would not be colored as expected
- [**Models**] Fixed excess drones being assigned to position 0,0,0