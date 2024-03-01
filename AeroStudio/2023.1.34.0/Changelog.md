# AERO Studio - 2023.1.34.0

## Enhancements

- Video projection reading is now performed asynchronously and has no impact on preview framerate while in edit mode. The frame will simply be loaded as soon as it is available

## Changes

- Exclude from lighting has been returned to the Formation Element options. It is now properly implemented.

## Bug Fixes

- Fixed double free that could happen with editable geometry scene views
- Fixed issue where strobe was acting like a constant light event
- Fixed issue where re-ordering channels did not affect the light layer evaluation order
- Fixed issue where when selecting between events with the same ID and start/end times, the inspector would resolve to the wrong event
- Fixed issue where when selecting between events with the same ID and start/end times, previously selected events may remain selected
