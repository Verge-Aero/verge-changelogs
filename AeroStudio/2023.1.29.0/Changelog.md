# AERO Studio - 2023.1.29.0

## Enhancements

- Creating a formation group made of formation sequences will now divide weights appropriately
- Added support for Circles (Ellipses were previously the only option) in the SVG importer
- Formation Groups can now draw their contents independently. This is used for displaying Array Objects with a formation group as its target
- Added the ability to decompose a compound shape (A Text Shape) into its parts
- Modifying a spline will now immediately update the state of any objects referencing it
- Starting a render will now set the state of the object according to the earliest state of all interp events in its timeline
- There is now an option that causes scaling of animation events to scale the ratio between keyframes
- Track events are now visualized in the dope sheet
- Added copy/paste support for keyframes
- A different symbol is now used to differentiate properties in the dopesheet
- Added a shortcut key for adding keyframes
- Shortcuts for 1-Dimensional scrolling on the animation editor
- Delete key can now be used to delete keyframes
- Playhead now snaps to the nearest keyframes depending on zoom level
- Animation editor and main timelines are now synced in time

## Changes

- Changed Formation Group to default to 'Flexible' mode
- Changed Formation Sequence to default to 'Flexible' mode
- Track distance now defaults to 0 (This no longer serves much purpose with the intro of sequences and may be moved or removed)
- Animation editor is now restricted to being greater than 0
- Animation graph editor line thickness has been reduced

## Bug Fixes

- Fixed preview not matching result when using partial splines
- Fixed stagger not being accounted for when showing whether a transition is long enough
- Fixed issue where render settings were not being reset when creating a new show
- Fixed issue where circle bounds were using radius rather than diameter for width and height
- Fixed exception that would occur when copying or loading a spline that is disabled
- Fixed not being able to use a spline as the target of a path modifier
- Fixed issue where creating a path modifier and assigning a path would result in an exception
- Fixed issue where an incorrect proxy object could be assigned to a target object
- Addressed a memory leak that would occur when computing the centroid of spline point selections
- Fixed issue where deleting anchor points from multiple splines at once would cause an exception
- Fixed issue where deleting the first point in an open spline (non-looping) would still force the next point to complete the loop
- Stopped animation editor from flickering when being resized
- Fixed issue where the playhead could not be moved manually when playing in the animation editor
- Fixed auto keyframes sometimes still being created even when auto keyframing is turned off
- Fixed animation editor snapping back to 0s-60s after each render