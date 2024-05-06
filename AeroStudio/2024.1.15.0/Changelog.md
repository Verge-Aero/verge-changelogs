# AERO Studio - 2024.1.15.0

## Features

- [Lighting] Added ability to reverse the direction of a shape chase

## Enhancements
- [Show Effects] Converting a scene object into a show effect will now retime all events so that the earliest event begins at 0 and all others adjust accordingly
- [Show Effects] When publishing a show effect, the default drone count will now refer to existing launch pads to provide a more relevant default value

## Bug Fixes

- [Geometry Modifiers] Fixed issue where an axis option for the taper modifer could cause the studio to lock up
- [Show Effects] Fixed issue where new show effect versions could not be published after deleting one of their child scene objects
- [Show Effects] Fixed issue where show effects containing formation sequences would not properly instantiate in the composer (scale set to 0, 0, 0)
- [Show Effects] Converting a scene object to a show effect now properly sets the generated Sequence event to a time that encapsulates all of its events
- [Composer] Fixed issue where canceling a render that was initiated from the composer would not return the user to the composer