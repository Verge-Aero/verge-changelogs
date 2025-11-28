# AERO Studio - 2025.3.7

## Features

- [**Timeline**] Added ability to set an event as the timeline reference. Zero will start where the selected event starts
- [**AI**] Added support for embedding AI models directly inside of the Studio

### Node Graph Editor
- [**Templates**] Load built-in templates to quickly start working with a formation
- [**Asynchronous Solver**] Solve complex graphs in the background with no slowdown
- [**Formation Graph**] Visual way to design and manipulate formations
- [**AI Nodes**] Added nodes that can be used to convert image data into formations or generate them from nothing
  - **Image To Formation**: Convert an image into an optimally placed set of points
  - **Image To Depth**: Convert a color image into a depth map
  - **Generate Image**: Generate a source image from a prompt and style input

- [**Geometry Nodes**] 
  - **Depth Extrusion Node**: Apply a depth map to extrude a formation in the Z direction
- [**Math Nodes**] 
  - **Multiply**
  - **Divide**
  - **Add**
  - **Subtract**

- [**Source Nodes**]
  - **Texture Node**: Load an image from file to use as an input
  
## Enhancements

- [**Storyboard**] Improved UI for storyboard importing
- [**Storyboard**] Allows user to choose an org for import options
- [**Interp Events**] Added support for Vector2 fields
- [**Sphere Projection Modifier**] Weighting can now be animated
- [**License Panel**] Simplified UI and improved experience

## Bug Fixes

- [**Timeline**] Fixed undo/redo not working for events
- [**Assets**] Fixed assets window not being responsive or loading incorrectly in some scenarios
- [**Formation Group**] Fixed "To Formation Group" button not correctly handling discrete slot objects
- [**Interp Events**] Fixed interp settings not saving correctly
- [**Point Clouds**] Fixed issue where points wouldn't turn yellow when selected after converting a shape to a point cloud
- [**Simulation**] Fixed a number of cases where a failure or a cancellation would result in a bad editor state