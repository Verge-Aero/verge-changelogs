# AERO Studio - 2023.1.32.0

## Enhancements

- Added optional spacing field to ASF header file. It defaults to one fifth of the glyph bounds
- Video projection now uses FFMPEG directly resulting in hitchless full-speed renders. Render times with projections are more than 10 times faster.

## Changes

- "Exclude from lighting" on Formation Elements is temporarily hidden on this build but will be added immediately back next patch when the associated crash is fixed

## Bug Fixes

- Fixed issue where when loading a video projection, an exception would occur
- Fixed issue where the projection viewport could exceed the available data buffer and cause a crash
- Fixed issue where modifiers were not being applied to base object in an Object Array
- Fixed issue where bounds were not being calculated correctly on point clouds for text glyphs
- Fixed issue where the texture format for projection video was causing the channels to be mixed improperly. This commonly resulted in a video with full red channels
