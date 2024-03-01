# AERO Studio - 2023.1.35.0

## Enhancements

- Added an "Add Layer" button to the Light Mixer Inspector
- Login has now been migrated to new cloud backend
- Added Dev-only unlock for modifying acceleration limits for testing purposes. This is only supported up to 5 drones.

## Bug Fixes

- Fixed crash that would occur when projection positions were injected with nan values and the mode was set to clear
- Fixed issue where volume lighting layer events following other volume lighting layers may be improperly masked
- Fixed "Invert" toggle not saving on QR code formations
- Fixed issue where orthographic raycasts were not being calculated properly
- Fixed issue where Move Along Spline events would not support the new spline objects
