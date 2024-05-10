# Unity Scripting Define Symbol Editor

## Introduction
The Unity Scripting Define Symbol Editor, developed by `com.Klazapp`, is a powerful Unity Editor extension designed to enhance the management of scripting define symbols. This tool simplifies the process of adding, modifying, and removing conditional compilation symbols specific to various build targets, streamlining the workflow for handling project settings directly within the Unity Editor.

## Features
- **Symbol Management**: Allows for the addition, application, and removal of scripting define symbols directly through the Unity Editor.
- **Target-Specific Symbols**: Provides the capability to manage symbols for specific build targets such as Android and iOS, with the option to extend support to other platforms.
- **Symbol Validation**: Ensures that only valid symbols are added or modified, preventing potential build errors.
- **Dynamic Discovery**: Automatically detects and lists all scripting define symbols used within the project, making them easily manageable through the editor interface.

## Dependencies
- Requires Unity 2020.3 LTS or newer to ensure compatibility and stability.

## Compatibility
| Compatibility | URP | BRP | HDRP |
|---------------|-----|-----|------|
| Compatible    | ✔️   | ✔️   | ✔️    |

## Installation
1. Download the package from the [GitHub Releases page](https://github.com/klazapp/unity-scripting-define-symbol-editor/releases).
2. Import the package into your Unity project via `Assets -> Import Package -> Custom Package`.
3. Access the tool from the Unity menu bar at `Klazapp -> Tools -> Scripting Define Symbols Editor`.

## Usage
To use the Scripting Define Symbol Editor:
1. Open the editor window by navigating to `Klazapp -> Tools -> Scripting Define Symbols Editor` in the Unity menu.
2. To add a new symbol:
   - Enter the symbol name in the provided input field.
   - Click `Apply & Create` to add the symbol to the selected build targets.
3. To manage existing symbols:
   - Use the `Apply` button to add the symbol to the build target’s defined symbols.
   - Use the `Remove` button to delete the symbol from the build target’s defined symbols.

## Customization
Symbols are prefixed by default with `KLAZAPP_` to ensure they are distinct from other project symbols. This prefix can be modified in the script to align with different naming conventions as required by the project.

## Known Issues
- There is no automatic synchronization of symbols across different workstations or version control systems, requiring manual management of the `ProjectSettings` file.

## To-Do List (Future Features)
- Expand support to include additional build targets.
- Enhance the user interface for better aesthetics and usability.
- Implement features for automatic synchronization with version control systems.

## License
This package is freely distributed under the MIT License, providing flexibility for both personal and commercial use. See the LICENSE file for more details.
