# AERO Studio - 2025.2.0

## Features

- [**Pyro**] Embeds new "geocheck" trigger safety mechanism
- [**Launching**] Added ability to stagger launch to the slot closest to a drone's position on the launchpad
- [**AI**] Added AI scene object that allows point clouds to be generated from prompts
- [**Storyboards**] Added AI scene object that allows point clouds to be generated from prompts
- [**Cylinder**] Added new cylinder scene object

## Enhancements

- [**Formation Groups**] Spline hulls are now slot count-limited correctly as part of formation groups
- [**Launchpad**] Launchpads can now be enabled/disabled. Disabled launchpads will be excluded from rendering
- [**Point Cloud**] Static point clouds can now be imported via CSV
- [**Circle Fill**] Added new solver option (Equal Area Rings) for circle fill

## Bug Fixes

- [**Rendering**] Fixed RTH setting failing during cloud renders/simulations
- [**Pyro**] Fixed issues caused by pyro product names being too long
- [**Packed Shows**] Fixed "removing broken references" on export not properly removing references
- [**Splines**] Fixed crash that could occur while using segment selection mode for splines using the hull slot solver
- [**Track Events**] Stopped being able to assign slot sources between show effects or from within a show effect to a launchpad
- [**Point Cloud**] Fixed crash that would occur when modifying a point cloud and then opening a new show
- [**Spline Tools**] Fixed split not working on vertices when in handle selection mode
- [**Spline Tools**] Fixed split button becoming clickable when not selecting a compound spline
- [**Window**] Restored the ability to resize the window when in windowed mode
- [**Text Shape**] Fixed anchor offset not having any effect on the shape
- [**Flocking Controller**] Fixed issue where saving flocking events would cause loading issues
