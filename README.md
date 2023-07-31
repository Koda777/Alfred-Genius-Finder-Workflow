# Intelligent Finder Workflow for Alfred

## Overview

This workflow for Alfred smartly calls Finder on macOS. If Finder is already open, it moves it to the current workflow using yabai. This is designed to circumvent the default behavior exhibited by Apple when opening applications with Alfred, where it opens them on the workspace where they were last, rather than where the user has called them.

## Requirements

- Alfred with Powerpack
- yabai (a tiling window manager for macOS)

## Installation

1. Download the `.alfredworkflow` file.
2. Double-click the file to import it into Alfred.
3. Ensure yabai is installed and running on your system.

## Usage

Once installed, you can invoke this workflow in Alfred. When called, it will intelligently handle the Finder window, moving it to the current workspace if it is already open.

## Why This Workflow?

Apple's default behavior when using Alfred to open applications can be inconvenient for those who rely on specific workspace arrangements. This workflow addresses that problem by ensuring that Finder opens (or moves to) the workspace where it was invoked.

## Contributing

If you have any suggestions or improvements, please feel free to fork the project and create a pull request.

## License

Please see the attached license file for details on how you can use, distribute, and contribute to this project.
