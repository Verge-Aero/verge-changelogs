# AERO Studio - 2024.1.12.0

## Changes

- [Scene View] Reduced the size of spline crosshairs by 75%
- [Scene View] Spline centroid crosshairs are now only drawn when selected

## Bug Fixes

- [OSX] Fixed issue where some folder/file selection dialogs did not work
- [Rendering] Fixed issue where rendering with a show effect that has no sequence would cause the render to lock at no progress
- [Show Effects] Fixed issue where a show effect with no contents would not load correctly
- [Light Mixer] Removed light addressing UI option because it is unfinished and causes crashes when enabled
- [Point Clouds] Fixed issue where importing a point cloud animation with HDR colors would result in a corrupt color animation
