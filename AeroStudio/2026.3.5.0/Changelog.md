# AERO Studio - 2026.3.5.0

## Features

- [**Track Event Lighting**] Reworked Track Event lighting into a crossfade overlay model, allowing traversal looks and reveal effects to layer over the normal object-to-object lighting blend instead of forcing transitions through black
- [**Track Event Lighting**] Added support for pre-start cover timing so an upcoming Track Event can begin its lighting transition before motion starts
- [**Track Event Lighting**] Added multiplicative traversal mode so effects like sparkle can modulate the underlying tracked colors rather than replacing them
- [**Track Event Lighting**] Added a dedicated blackout path for intentional fade-to-black transitions

## Improvements

- [**Timeline Toolbar**] Timeline signal panel preferences now persist between sessions, including display mode, tag visibility, track event linking, linked scaling, linked timeline visibility, and playback speed
- [**Track Event Lighting**] New/default track lighting now uses the Sparkle crossfade behavior by default, including Sparkle Reveal for cover and reveal transitions

## Changes

- [**Timeline**] Track Event linking now defaults to off so linked events can be viewed without automatically manipulating them
- [**Track Event Lighting**] Exit-style fade controls have been replaced by the crossfade overlay workflow: Cover, Traversal, and Reveal
