# AERO Studio - 2025.1.10

## Improvements

- [**Spline**] Reverse/Open/Close can now be used when not in edit mode for a spline
- [**Formation Group**] Added undo/redo support for deleting formation group elements
- [**Formation Group**] Added undo/redo support for creating formation group elements
- [**Formation Group**] Added undo/redo support for reorganizing formation group elements
- [**Compound Spline**] Added undo/redo support for deleting formation group elements
- [**Compound Spline**] Added undo/redo support for creating formation group elements
- [**Compound Spline**] Added undo/redo support for reorganizing formation group elements
  
## Bug Fixes

- [**Spline**] Fixed error that would occur when undoing a spline merge
- [**Spline**] Fixed crash that could occur when deleting a spline endpoint
- [**Spline**] Fixed undo of closing/opening a spline not setting its closed state properly
- [**Inspector**] Fixed issue where scene reference fields would not be updated properly when it pointed to a deleted object
- [**Formation Group**] Fixed maximum slot field being labeled as "minimum"
- [**Formation Group**] Fixed min/max UI elements being displayed for "Fixed" allocation mode
- [**Formation Group**] Will now always allocated at least the minimum number of slots necessary to fulfill its elements
- [**Formation Group**] Modifying formation element properties will now properly update the scene preview
- [**Formation Group**] Fixed deleted references showing as their original scene object name in the list view
- [**Compound Spline**] Fixed issue where deleting single anchor points would not work for compound splines
- [**Compound Spline**] When undoing a delete, splines are now placed in their proper order
