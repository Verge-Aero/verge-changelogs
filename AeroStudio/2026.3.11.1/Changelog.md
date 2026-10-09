# AERO Studio - 2026.3.11.1

## Features

- [**Path3 Import**] Added support for importing DSS Path3 ZIP archives and individual `.path3` files as animated scene point clouds for tracking, including positions and RGB colors at their original sample rates.
- [**Point Sorting**] Added spatial sorting controls for static point clouds and the Image to Formation node, including axis-based ordering, middle-out, and outside-in. Point colors remain paired with their positions, and static point-cloud sorting supports undo and redo.

## Enhancements

- [**Project Views**] Show projects now restore the saved scene-view camera position, orientation, zoom, projection, navigation mode, and orbit pivot when reopened.
- [**Animated Point Clouds**] The inspector now displays position and color frame counts and sample rates.

## Bug Fixes

- [**Track Linking**] Fixed linked-event selections and timeline visibility being lost when changing track selections or completing a range selection.
- [**Track Linking**] Fixed directly selected linked events being moved or scaled twice during linked track edits.
- [**Layer Locks**] Fixed choreography layer locks not being restored after saving and reopening a show, and lock indicators clearing while another channel in the layer remains locked.
- [**Splines**] Fixed uneven slot spacing and incorrect distance offsets across spline spans, including slots near the end of a spline.
- [**Spatial Gradients**] Fixed lighting differences between the scene preview and rendered output when objects are translated, rotated, or scaled.
- [**Return to Home**] Fixed geofence update commands being inserted into rendered return-to-home branches.
- [**Project Serialization**] Fixed saving and loading incomplete interpolation data with missing values or references.
- [**Project Serialization**] Fixed incorrect serialization of vector, rotation, and matrix components in array-form data.
- [**CSV Import**] Fixed animated CSV position and sample-rate parsing on systems that use a comma as the decimal separator.
- [**Animated Point Clouds**] Fixed frame indexing and buffer sizing for large animation caches.