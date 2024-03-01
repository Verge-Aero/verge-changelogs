# AERO Studio - 2023.1.75.0

## Features

- Expanded debug menu
- Added render capture for transitions to view states for each formation sequence and track event
- Added option to view transitions between slots during track events
- Added a button to launchpads to automatically shift the 3D map to their altitude

## Enhancements

- Now uses the Google Maps Elevation API to make an initial altitude estimation for 3D tiles

## Bug Fixes

- Fixed modifier enable toggles not being obeyed
- Fixed importing point-cloud fonts causing all black textures to be replaced with the last point-cloud image
- Fixed drone draw toggle not being obeyed
- Fixed transition times not being accurate due to incorrect drone counts
- Fixed transition times not applying geometry modifiers to objects
- Fixed transition times using incorrect slot matching
- Fixed track event draw happening twice per frame instead of once
- Fixed stagger always being enabled
- Fixed issue where transitioning from a formation sequence that is post-transition would result in incorrect slot-matching
- Fixed slow video rendering when including audio in render
