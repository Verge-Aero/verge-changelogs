# AERO Studio - 2023.1.54.0

## Enhancements

- Removed unnecessary logging for model imports

## Bug Fixes

- Fixed shape chase light fading not working
- Fixed interpolation events not updating in preview
- Fixed ripple modifier causing drones to stop moving in cases where a bounds dimension was 0 length
- Fixed splines not computing bounds before being modified. This would lead to strange modifier behavior
