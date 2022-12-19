# DMX Controller Release
Release for my PyQT5 / Arduino DMX controller

# Current Latest Release: 0.0.1

This build is for linux and windows. The windows version includes a setup installer.

# 0.0.1 release notes:

# 0.0.1 release for windows

Warning! This is not a finished version. Bugs are highly likely. All sliders now send DMX values, *other than the strobe channel*. The windows installer.
Bugs should be caught by a custom error dialog. If this occurs, please create an issue on this page, with what you were doing and the error dialog produced. The exception is a Port Error, which means the console is unreachable. DMX Controller requires the console to be plugged in to work properly. A demo version is coming soon.

## Functionality

- Sliders send DMX
- Sliders can adjust the colour box to preview
- Sliders can have values manually entered
- 3 fixture files are packaged with the app, and are in JSON format
- Patching can be done via the show file (only test_show.json is readable!)

## Missing Features

- Working strobe slider
- Channels with multiple functionalities won't work as of yet
- The graphics view is proving difficult to implement, so only the first patched fixture is available

### WARNINGS
- **_Window resolution and widget scaling may be off!_**
- DONT change values like showID and fixtureID, these may break the software!

## Releases

- Windows is the target platform for this release, with a Linux version to follow. Please navigate through the directories to find the correct release.
- There is currently no known minimum system requirements. Less than 1 GB of space is needed for the installation. There will be a way to list your system specs and the performance in the future to help us generate the required and recommended hardware, but it should be very low for the moment. 