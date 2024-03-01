# AERO Studio - 2023.1.66.0

## Features

- Added back the ability to enable/disable lighting crossfades
- Added time-based easing for interpolation functions

## Enhancements

- Major changes to SVG importer to support a node-based tree structure
  - Groups and layers are now imported properly into the hierarchy
  - Group or layer colors and transforms are now applied to nested shapes
- Switching from corner to any other control mode for spline anchors shifts the control points to be clearly selectable

## Changes

- Spline toolset selector now defaults to handle manipulation
- Default selection weighting is now set to 2

## Bug Fixes

- Fixed an issue where certain SVGs would not import properly
- Fixed SVGs with matrix transforms not importing in the proper orientation
- Fixed issue where timeline keyframes can't be dragged if playhead over event
- Fixed issue where selecting a spline anchor and manipulating it could result in manipulating a previous anchor
- Fixed single clicks causing a drag operation to trigger
- Fixed anchor mode selection always displaying "Free"
