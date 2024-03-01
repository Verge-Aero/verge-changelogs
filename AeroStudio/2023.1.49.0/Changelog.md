# AERO Studio - 2023.1.49.0

## Enhancements

- Transform rotations can now be set beyond +-180 degrees allowing revolutions to be represented properly
- Enhanced keyframe inspector
- The keyframe inspector will now display all animated properties on the selected objects at the timestamp of the selected keyframe
- Properties are laid out in a more organized/readable form
- Only selected keyframes will have interactable input fields
- Multiple keyframes can be selected to make their fields interactable in the inspector (as long as they share the same timestamp)
- Keyframe representation on timeline
- Animation events will now display their root keyframes
- These keyframes are equivalent to the highest level keyframe on the dope sheet for all intents and purposes. This means all keyframes with the same timestamp (even across events) will be modified together
- Keyframes can be selected to bring up inspector values, or dragged directly in the timeline to set a new timestamp
- Improved workflow for animating rotation values
- Improved scene view performance by removing scene views for choreography events

## Bug Fixes

- Fixed issue where deleting an animation layer in the animation editor and returning to the timeline could in some cases cause the timeline to lock up
- Fixed land event properties not being saved properly
- Fixed issue where Shift-dragging an object to duplicate it would manipulate the previous object for a single frame
- Fixed issue where right fill was not working
- Fixed issue where in-to-out fill was not mixing the unfilled section properly
- Fixed issue where inspector entry properties were being ignored in some cases
- Fixed issue where svg paths were not parsing properly when a second radix point was being used as a delimiter
- Fixed sparkle events causing legacy Vfabs to not import properly
- Fixed volumetric light mixers causing legacy vfabs to not import properly
- Fixed modifiers on BezierSpline3D objects causing legacy vfabs to not import properly
