# AERO Studio - 2023.1.52.0

## Features

- Added new "Free" keyframe relationship to events. Keyframes will remain at the same real time when their events are resized

## Enhancements

- Extended landing extension from 3 meters below starting point to 10 meters. This should address cases where users are launching from an excess altitude offset and failing to reach the ground on return
- Changes in the keyframe inspector are now immediately reflected in the scene view
- Keyframe shortcut key commands (add, delete, undo, redo) are now immediately reflected on the main timeline
- Timeline keyframes are now larger and easier to select
- Newly added animation events as a result of keyframe creation will now place the first keyframe in the center of the event (at the playhead time)
- Keyframes can only be manipulated from the main timeline if their respective events are selected
- Keyframes on the main timeline now have 3 colors to denote their states: dark gray (uninteractable until event is selected), light gray (unselected), and yellow (selected)

## Bug Fixes

- Fixed drones being slightly offset while landing below the ground
- Fixed last-resort land sequence not being triggered in the vbake output (this should have been triggered after the drone already attempted to travel 3 meters beneath the launch altitude)
- Slashes are not valid file characters so it causes issues on export when a scene object name contains them. Slashes are automatically converted to underscores to address this when saving vfabs
- Fixed issue where splines were being improperly sampled when "Use Pivot Weighting" was not checked
- Fixed issue where flocking events on the timeline were being added and not removed when fired during a render. This would lead to duplicate events every time a render occurred
- Dependency handles are now used for calculating local bounds which addresses certain cases where bounds were calculated while also attempting to solve slots leading to accessing invalid data. This is a large change so look for unexpected behavior related to modifiers
- Fixed projection lighting not obeying fade in or fade out
- Clicking on a keyframe in the animation editor is less likely to initiate an accidental drag
- Fixed activation panel appearing behind the project panel
- Fixed activation panel not scaling appropriately
- Fixed issue where sparkle lighting was accessing incorrect data locations for certain slot indices
