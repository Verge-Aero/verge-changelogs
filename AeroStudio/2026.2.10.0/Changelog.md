# AERO Studio - 2026.2.10.0

## Features

- [**Models**] Added support for tracking skinned/animated meshes
- [**Models**] Added ability to choose between Material/Texture/Vertex colors as color sources

## Improvements

- [**Pyro Events**] Cue targets and alternating variables transfer when switching event type
- [**Graphics**] Significantly improves the performance of drawing drones in the scene or render views
- [**Launchpad**] Significantly optimizes the time it takes to compute the staggered launch preview/sequence
- [**Launchpad**] Removes long hitch that would happen when deselecting the launchpad at high drone counts
- [**Launchpad**] Doubled max drone count to 20,000
- [**Models**] Removed inspector items that are no longer supported/unimplemented
- 
## Bug Fixes

- [**Light Mixer**] Fixed potential simulation failure
- [**Show Effects**] Fixed issue where unpacking and manipulating a show effect could lead to unexpected behavior
- [**Editor**] Fixed crash in safety distance/density light modes
- [**Editor**] Fixed crash in Formation Group previews
- [**Editor**] Fixed scene objects not appearing in hierarchy when added while in the environment menu