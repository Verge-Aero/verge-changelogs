# AERO Studio - 2023.1.31.0

## Features

- Arbitrary launchpad shapes now copy the previously selected formation to an editable point cloud. This enables a simpler way to set up arbitrary launchpads
- Launchpad shapes can now be modified with the shape's associated toolset
- Adds Polygon2D manipulation tools
- Adds Poisson Disc Sampling distribution for Polygon2D shapes
- Adds basic manipulation tools for Point Clouds
- Adds ability to reverse the direction on a spline
- Shift-dragging point cloud vertices will duplicate them
- Point clouds can be separated into new point clouds or merged into a single point cloud

## Enhancements

- Splines and Polygons now turn red when selected (and not in edit mode)
- Grid increment shifts to safe distance when modifying geometry
- Automatically resizes launch event when modifying drone count or providing the lacking space due to a subsequent event
- Adds an exclamation symbol and turns the text red when a launchpad is sized too short
- Adds an error prompt when trying to render and hitting a validation error
- Can now copy and paste from Google Maps to editor via environment window. Do this by right-clicking on the target location in Google Maps, clicking on the coordinates, then going to the Show Environment settings and clicking on the "Paste GPS from Clipboard" button
- Point cloud vertices change size and color when selected
- VFabs : BezierSpline3Ds are now converted to the new Spline format on import

## Changes

- Changed default chase type to "Sine"

## Bug Fixes

- Fixed issue where some integer fields would apply while dragging, but reset afterward when using the spinner
- Fixed issue where drag copying objects would cause the handle to reset and deselect the object
- Fixed issue where deleting some objects and then performing an undo would cause a crash
- Fixed issue where deleting some objects with specific sub-objects would cause a crash
