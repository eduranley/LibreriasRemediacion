# .NET Libraries

This directory contains .NET libraries and assemblies used for remediation projects.

## Structure

Organize your .NET libraries using the following structure:

```
dotnet/
├── remediation-tools/        # .NET tools for remediation tasks
├── security-patches/         # Security patches and fixes
├── dependency-updates/       # Updated versions of vulnerable packages
└── custom-assemblies/        # Custom .NET assemblies for specific issues
```

## Usage

- Place NuGet packages (.nupkg files) or DLL files in appropriate subdirectories
- Include project files (.csproj) when applicable
- Document any specific .NET Framework or .NET Core version requirements

## Adding Libraries

1. Create appropriate subdirectory if it doesn't exist
2. Add the package or assembly file(s)
3. Create a README.md with usage instructions
4. Include project file or package reference information