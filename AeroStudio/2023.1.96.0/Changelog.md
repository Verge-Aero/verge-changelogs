# AERO Studio - 2023.1.96.0

## Bug Fixes

- Fixed issue where missing mesh or point cloud file references could cause application instability
- Fixed issue where loading missing references would cause formation group fixed slot counts to reset to 0
- Fixed issue where fixing file references for animated point clouds would still result in an empty point cloud
- Fixed Frame Animation event previews being calculated incorrectly resulting in mismatch with renders
- Fixed Video Projection Event causing errors when not cleaned up properly when an event ends
- Fixed issue where dropping launch transition time below 3 seconds would cause the last launched drone to perform unexpectedly. Note: This would also manifest in the drone not properly joining the land formation, causing the trays to never land
- Fixed transition time during launch not being calculated properly
