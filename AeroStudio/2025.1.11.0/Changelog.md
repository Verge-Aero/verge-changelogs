# AERO Studio - 2025.1.11

## Improvements

- [**Formation Group**] Flexible mode for discrete shapes where minimum or maximum overrides are not set will now default to the max value
- [**Formation Group**] Added a new "Strict" allocation mode that will enforce that fixed allocation modes for formation groups are obeyed. This will be the new default behavior in the future
- [**Launchpads**] Previews are now drawn all the time, even if the launchpad is hidden. This was previously confusing for users

## Bug Fixes

- [**Paint Tool**] Fixed issue where deleting all palettes would cause the paint tool to exhibit multiple issues
- [**Splines**] Fixed issue where selecting a spline, loading a new show, and then selecting a new spline would cause a crash
- [**Pyro Trigger**] Fixed cases where drones at the end of a trigger sequence may not fire depending on event length