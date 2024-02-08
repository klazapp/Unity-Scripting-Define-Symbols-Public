# Inspector Utility for Unity

## Introduction
The `Scripting Define Symbols` utility, part of the `com.Klazapp.Utility` namespace, are compiler directives that allow you to define custom symbols that can be used to include or exclude specific sections of code during compilation. These symbols provide a way to conditionally compile different parts of your code based on the defined symbols.

## Features
- Scripting Define Symbols enable conditional compilation, allowing you to include or exclude specific sections of code based on whether certain symbols are defined. This can be useful for platform-specific code, debug-specific features, or feature toggles.
- Symbols can be defined to include additional logging, debugging, or testing functionality in development builds while excluding them from release builds. This helps in debugging and testing your game or application during development without affecting the final build size or performance.
  
## Dependencies
To use `Scripting Define Symbols`, certain dependencies are required. Ensure these are included in your Unity project.
- **Unity Version**: Minimum Unity 2020.3 LTS.
- **Repository**: [LogMessage Unity Editor Helper](https://github.com/klazapp/Unity-Editor-Helper-Public.git)
- Unity Engine dll
- Unity Editor dll

## Compatibility
| Compatibility        | URP | BRP | HDRP |
|----------------------|-----|-----|------|
| Compatible           | ✔️  | ✔️  | ✔️   |

## Installation
1. Open the Unity Package Manager (`Window` > `Package Manager`).
2. Click `+`, select `Add package from git URL...`, and enter `https://github.com/klazapp/Unity-Scripting-Define-Symbols.git`.
3. Unity will download and make the package available in your project.

## Usage
```csharp
Write Something here
```

## To-Do List (Future Features)
- 

## License
This utility is released under the [MIT License](LICENSE).
