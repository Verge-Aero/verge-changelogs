# AERO Studio - 2024.2.66

## Features

- [**Light Volumes**] Added ability to invert volumes so that lighting affects everything *not* in a volume
- [**Geofence**] Added new "Predictive Hard Geofence" support. This is a new methodology that provides velocity-independent detection and flight termination to even further ensure drones do not leave their operational volume.
- [**Light Events**] Added multi-select edit support for primary color fields of light events
  
## Enhancements

- [**Spline**] Improved hull slot placement algorithm to be more robust against complex splines

## Changes

- [**Text Shape**] Changed default alignment to be lower-left to more closely fit previous behavior
- 
## Bug Fixes

- [**Point Clouds**] Fixed issue where converting a shape to point cloud that doesn't have enough slots would cause the designer to crash
- [**Spline**] Fixed issue where converting a primitive spline shape to an editable spline could cause a crash
- [**3D Tiles**] Fixed crash that would occur when loading some of the new Google Tiles