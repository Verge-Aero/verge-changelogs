# AERO Studio - 2023.1.50.0

## Bug Fixes

- Fixed issue where re-ordering channels that contained no events would cause an error that resulted in saving duplicated channels. Loading this file would result in strange designer behavior
- Added logic to automatically resolve any cases of duplicated channels so that the file can be safely opened
- Fixed case where moving an object while in an orthographic view would cause the camera to zoom in and out
- Fixed issue where typing in the bug report window would allow key presses to fallthrough and trigger hotkey actions
- Fixed issue where loading a show file without resolving an external model would cause loading to fail
- Fixed issue where loading a show file without resolving an external font could cause unexpected behavior
- Fixed issue where animation events would start in the wrong state when opening a file
- Fixed issue where production renders where there is no return event would only render 10 seconds of the production pass
- Fixed issue where events smaller than 100 milliseconds could not be shifted appropriately
