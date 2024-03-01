# AERO Studio - 2023.1.51.0

## Changes

- Launchpad shape transforms have been changed from 90 degrees to -90 degrees to bring them into line with local transform editing
  - Note that this will cause existing polygon launchpad shapes to be flipped along an axis

## Enhancements

- Changed Array Object local scale to default to 1,1,1 when reset
- Local space transforms now work in spline, point cloud, and polygon edit views

## Bug Fixes

- Fixed performance map export not working
- Fixed .kml being appended twice to performance map file
- Fixed alpha keys in gradient colors being evaluated incorrectly
- Fixed nesting an object in another object not adjusting its euler angles appropriately
- Fixed Rotation handle not operating on the correct axis when modifying the child of a transform
- Fixed issue where dragging over a transform handle would block selection operations
- Fixed issue where switching between local and global space handles was not working
