# AERO Studio - 2025.3.7

## Features

- [**Light Event**] Added blend modes to allow more control over how colors are combined

### Node Graph Editor

- [**Texture Nodes**] 
  - **Map Texture Node**: Apply a texture's colors to a formation via UV mapping
  - **Tint Texture Node**: Modify a texture's color

## Improvements

- [**Image-To-Formation**] Significantly increased the performance of the Image-To-Formation node
- [**Image-To-Formation**] Increased the output quality of the Image-To-Formation node

## Changes

- [**Show Settings**]: Removed minimum altitude setting as it is now located in the environment settings

## Bug Fixes

- [**Formation Graph**] Fixed crash that would happen when setting drone count to 0 on Image-To-Formation nodes
- [**Formation Graph**] Fixed color being darkened after applying math operations
- [**Formation Graph**] Fixed formation graphs not completing their solution before a track begins
- [**Formation Graph**] Addressed most modifiers not working correctly on Formation Graphs
- [**Formation Group**] Fixed "To Formation Group" button not correctly handling discrete slot objects
- [**External Model**] Fixed tracking imported models not working correctly