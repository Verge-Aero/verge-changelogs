# AERO Studio - 2026.3.2.0

## Features

### Point Cloud Paint Improvements

Point cloud painting now works directly from the normal scene view without requiring Point Cloud Edit Mode. Paint-capable point clouds use their per-point color cache by default, while other colorable objects continue to use the existing whole-object color behavior.

- Brush, bucket, and dropper tools now target point-cloud point colors when painting a point cloud.
- Point clouds using Solid Color or Gradient sources are converted into per-point colors when painting begins.
- Painted point clouds switch to per-point color mode automatically, preserving the visible color result while allowing localized edits.
- Non-point-cloud objects continue to use the existing whole-object color workflow.

### Soft Brush Falloff

The point-cloud paint brush now supports alpha falloff for softer, more natural color edits.

- Falloff controls the brush's soft edge from hard edge to center-to-edge fade.
- The paint gizmo shows both the outer brush radius and the inner full-strength radius.
- Brush size can still be adjusted with Primary + scroll.
- Brush falloff can be adjusted with Primary + Shift + scroll.
- A new falloff slider is available in the brush color picker controls.

### Point Cloud Paint Undo

Point-cloud paint operations now integrate with undo/redo.

- Each brush stroke commits as one undoable action.
- Bucket fills on point clouds are undoable.
- Undo/redo restores both point colors and the original color source.

## Compatibility

- Existing point clouds remain compatible.
- Point clouds using Solid Color or Gradient sources are converted to per-point colors when edited with point-cloud painting.
- Existing whole-object color painting remains the fallback for objects that do not support per-point painting.
- Point Cloud Edit Mode paint behavior is preserved and now shares the same point-cloud paint workflow as normal scene painting.

## Improvements

- [**Point Cloud Paint**] Added per-point paint support outside Point Cloud Edit Mode.
- [**Point Cloud Paint**] Added alpha falloff controls for brush painting.
- [**Point Cloud Paint**] Added undo/redo support for brush strokes and bucket fills.
- [**Point Cloud Paint**] Updated bucket painting to fill the point color cache for point clouds.
- [**Point Cloud Paint**] Updated dropper behavior to sample the visible point color on point clouds.
- [**Color Picker**] Added a brush falloff slider.
- [**Viewport Gizmo**] Added an inner brush circle to show the full-strength paint region.
