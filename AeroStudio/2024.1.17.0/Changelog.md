# AERO Studio - 2024.1.17.0

## Enhancements

- [SVG] Supports color style sheets and named colors in SVG files.
  - Covers more cases where importing an SVG results in improper colors
- [Splines] Anchor handles now scale based on distance from the camera

## Bug Fixes

- [Web] Fixed issue where some uploads that would take a long time would fail
- [Splines] Fixed issue where entering into edit mode could cause a crash
- [SVG] Fixed a case where multiple horizontal or vertical commands would cause an SVG to fail to load
- [SVG] Fixed edge case where some paths would have incorrect anchor points
