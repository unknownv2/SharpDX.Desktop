## SharpDX.Desktop for .NET Core 3.0

Updates the library to target .NET Core 3.0 instead of the .NET Framework. The other libraries required for use in SharpDX are released on NuGet targeting .NET Standard, so this is the only one we need to update since it requires Windows Forms. The code is not modified, just the project configuration was updated.

**[Building the library requires the .NET Core 3.0 SDK, which can be downloaded here.](https://dotnet.microsoft.com/download/dotnet-core/3.0)**

To build the library, run:

```
$ dotnet build
```

The original library can be found here: https://github.com/sharpdx/SharpDX.

