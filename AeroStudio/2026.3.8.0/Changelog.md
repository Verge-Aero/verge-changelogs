# AERO Studio - 2026.3.8.0

## Features

- Added Windows code signing support to reduce the chances that Windows flags it as unsafe
- Packed show export now stops when broken external file references are detected and opens the File Refs tab so references can be fixed before exporting.
- File Refs now highlights missing, invalid, and empty-path references and supports right-click removal of file references.

## Changes

- Improved macOS signing and notarization diagnostics.
- Updated submodules and project version.

## Bug Fixes

- Fixed environment settings not applying correctly to renders and preview state.
- Fixed removed external file references reappearing after saving and reloading.
