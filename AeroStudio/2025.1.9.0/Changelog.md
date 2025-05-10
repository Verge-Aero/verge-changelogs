# AERO Studio - 2025.1.9

## Bug Fixes

- [**Spline**] Fixed issue where bounds were being shared between splines that were copied/duplicated from one another
- [**Predicted Geofence**] Fixed issue where flights above 400 AGL could calculate an under-sized geofence which blocked show export
- [**Pyro**] Fixed manifest not exporting properly if any launchpad name was too long due to xlsx file format limits
- [**Show Effects**] Fixed slot configurations not saving properly
- [**Show Effects**] Fixed adding formation group elements not linking to their formation group properly