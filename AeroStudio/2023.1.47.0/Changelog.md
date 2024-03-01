# AERO Studio - 2023.1.47.0

## Bug Fixes

- Fixed issue where using a sphere in an array object would cause an exception and would not draw.
- Fixed issue where loading an interp event that contains vector3 values would cause renders to fail.
- Fixed crash that could occur when cleaning up a scene view for a polygon, spline, or point cloud that was being modified. This crash was most often happening when completing a render or loading a new show.
