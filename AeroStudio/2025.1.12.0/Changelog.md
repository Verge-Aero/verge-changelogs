# AERO Studio - 2025.1.12

## Improvements

- [**Splines**] Shift Anchor now obeys global vs local transform handles
- [**Compound Splines**] Compound spline can now be created from the shape palette
- [**Compound Splines**] Splines can now be assigned fixed slots counts within a compound spline

## Bug Fixes

- [**Splines**] Fixed issue where previously selected spline would remain selected
- [**Splines**] Fixed issue where the spline anchor couldn't be shifted if not in edit mode
- [**Splines**] Fixed crash that could happen when extruding the endpoints on a spline
- [**Splines**] Fixed crash related to redoing extrudes on a deselected spline
- [**Splines**] Fixed crash related to redoing subdivisions on a deselected spline
- [**Splines**] Fixed issue where duplicating splines in a compound spline could case bezier control point mode corruption