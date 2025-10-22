# .NET 8.0 Upgrade Plan

## Execution Steps

Execute steps below sequentially one by one in the order they are listed.

1. Validate that a .NET 8.0 SDK required for this upgrade is installed on the machine and if not, help to get it installed.
2. Ensure that the SDK version specified in global.json files is compatible with the .NET 8.0 upgrade.
3. Convert WpfAutoGrid\WpfAutoGrid.csproj to SDK-style project format.
4. Upgrade WpfAutoGrid\WpfAutoGrid.csproj to .NET 8.0.
5. Convert AutoGridExamples\AutoGridExamples.csproj to SDK-style project format.
6. Upgrade AutoGridExamples\AutoGridExamples.csproj to .NET 8.0.

## Settings

### Project upgrade details

#### WpfAutoGrid\WpfAutoGrid.csproj modifications

Project properties changes:
  - Project file needs to be converted to SDK-style project format
  - Target framework should be changed from `net4.8` to `net8.0-windows`

#### AutoGridExamples\AutoGridExamples.csproj modifications

Project properties changes:
  - Project file needs to be converted to SDK-style project format
  - Target framework should be changed from `net4.8` to `net8.0-windows`