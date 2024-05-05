# Changelogs

Owner: Christopher Franzwa
Created time: March 25, 2024 11:36 AM
[Notion Link](https://www.notion.so/Changelogs-75998dd3eba849fe890a59567f1a0760)

# Summary

Changelogs are all stored in the [verge-changelogs](https://github.com/Verge-Aero/verge-changelogs/tree/master) repo. *This repository is publically visible, so developers should be careful not to include any sensitive information in them.*

The format for changelogs should follow [App name]→[Major.Minor.Revision.Build]→changelog.md

Github has full support for in-place markdown rendering and external files such as images can be included within the directory of the markdown file to embed those files.

The following categories should be used for indicating the type of change:

- “Features” → These are functional additions that add the ability to do something new
- “Enhancements” → These are improvements to existing features that affect performance, robustness, or reliability
- “Bug Fixes” → These are fixes to issues that were producing unintended results
    - Entries generally start with “Fixed”
- “Changes” → These are updates that don’t fit into any of the other bins. They are adjustments that are minor, but important enough to relay to the end user

See the below example for formatting 

# Example

```markdown
# #1 Best Software in the World - 2024.1.1.0

## Features

- Added a UI that convinces the user that they should leave the drone show industry

## Changes

- Aero Studio name changed to "#1 Best software in the world"

## Enhancements

- Improves renders so that they complete before the user even presses the button

## Bug Fixes

- Fixed literally every bug
- Fixed over-confidence about fixing every bug

![Alt Text](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExam96enZjbzVodWJlMHY3N29vZ3N0NmR1aTllamViZTFkMjhoaTA4MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/GeimqsH0TLDt4tScGw/giphy.gif)

```