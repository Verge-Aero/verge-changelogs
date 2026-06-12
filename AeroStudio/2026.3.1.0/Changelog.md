# AERO Studio - 2026.3.1.0

## Features

### Smarter Track Event Editing

Track Events can now bring their related timing events along for the ride. When linking is enabled, moving, scaling, swapping, or normalizing a Track Event can also update the events found under the tracked scene object hierarchy.

- Complex formation, modifier, and lighting setups can be moved as one creative unit.
- Linked events are resolved dynamically, so newly added child-object events can be included automatically.
- Linked timelines can be shown while editing, making it easier to adjust sub-events without losing context.
- Linked operations support undo/redo.

### Track Event Lighting

Track Events now support built-in arrival and exit lighting. This lets designers keep drones dark before arrival, show a temporary traversal look while drones move, reveal into the tracked output, and fade back to black at the end.

- Dedicated Track Event lighting controls for Traversal, Reveal, and Exit.
- Expanded Drone Channel lighting sub-lane for easier timing edits.
- Larger lighting blocks with labels, handles, and ramp graphics.
- Timing stays user-friendly when Track Event length or transition duration changes.
- Presets such as Reveal While Moving, Arrive Then Reveal, Sparkle Traversal Then Reveal, Glow Traversal Then Reveal, and Blackout Exit.

### Expanded Fade And Transition Effects

Fade In/Out controls now support more than simple alpha fades. Transition effects can reveal or hide lighting per point for more expressive looks.

Available transition styles include:

- Alpha
- Shape Fill
- Sparkle Reveal
- Chase Ripple
- Random Dissolve
- Height Sweep
- Radial Burst
- Noise Cloud

These transitions are shared across Light Mixer fades, Track Event lighting reveal/exit behavior, and Fade Light Layer workflows where applicable.

### New Spatial Lighting Effects

Several new Light Layer effects were added for richer drone lighting without building complex multi-event stacks.

New effects:

- Spatial Gradient: animated color fields mapped across position, height, radius, or slot order.
- Spiral Sweep: rotating radial sweeps for beacon, galaxy, or radar-like motion.
- Cellular Bloom: organic procedural blooms that radiate color from cell centers.
- Meteor Shower: moving streaks and slash-like passes across a formation.

These effects are available from lighting event creation menus and compatible layer pickers.

### Cross-Channel Move, Copy, And Paste

Events can now be moved or copied between compatible channels, including channels on different scene objects.

- Drag events between compatible channels.
- Copy/paste selected events with Ctrl/Cmd+C and Ctrl/Cmd+V.
- Multi-channel selections map onto contiguous compatible destination channels.
- Drag ghosts preview placement before dropping.
- Undo/redo is supported.

### Faster Timeline Navigation

Timeline navigation is smoother and more consistent across the editing surface.

- Scroll over channels and events to move vertically through the channel viewport.
- Side-scroll and horizontal scrollbar support for timeline panning.
- Middle-click drag pans from timeline panels, channels, and event surfaces.
- Events can be clicked and dragged immediately without a separate select-first click.

### Faster Channel Setup

Toolbar shortcuts were added for quickly creating common channel types on compatible selected scene objects.

Supported shortcuts include:

- Transform Channel
- Lighting Channel
- Animation Channel
- Payload Layer Channel

Lighting channel creation can add a light mixer component automatically when needed.

## Compatibility

- Existing shows remain compatible.
- Track Event linking is dynamic and does not permanently store link membership.
- Track Event lighting remains disabled on old saved Track Events unless explicitly enabled.
- Cross-channel transfer compatibility is based on matching concrete channel types in this release.

## Improvements

- [**Rotation Event**] Added button to swap from - to rotation values
- [**Rotation Event**] Added button to reset "to" rotation to "from" rotation
- [**Rotation Event**] Overhauled inspector for rotation events
- [**Rotation Event**] Added "Sweep" mode that rotates back and forth
- [**Rotation Event**] Adds presets for "Sweep" mode
- [**Scene Hierarchy**] Added option to create and nest content in a new node, resetting the local transform
- [**Scene Hierarchy**] Support copy + paste of hierarchy nodes / "Duplicate" context option

## Bug Fixes

- [**License**] Fixed issue where swapping email accounts did not swap product keys
- [**Spline**] Fixed converting a spline into a compound spline causing events to be wiped
 