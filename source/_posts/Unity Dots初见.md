# Unity Dots初见

## Installation and Setup

### Unity Editor version

2020.3.30+ or 2021.3.4+ with entities version: 0.51

### IDE support

Entities uses the [Microsoft Source Generator](https://docs.microsoft.com/en-us/dotnet/csharp/roslyn-sdk/source-generators-overview) feature for its code generation, which means it needs a high ide version.

Visual Studio 2022+

Rider 2021.3.3+

### Package installation

The Entities package isn't listed in the Package Manager, even if you've enabled the `Preview Packages` setting. You can use the following ways to install the Entities package:

1. Use `Add package from git URL` under the `+` menu at the top left of the package manager to add packages either by name (such as  `com.unity.entities`) or by Git URL (but this option isn't available for DOTS packages). If you want to use a Git URL instead of just a name in the Package Manager, you must have the git command line tools installed.
2. Directly edit the `Packages\manifest.json` file in the Unity project. 

com.unity.entities

com.unity.rendering.hybrid