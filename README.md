# Blazor DataGrid - Bind JSON Object to Grid

## Overview

This sample demonstrates how to bind JSON data to the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) and display the records in a tabular format. The application loads data from a JSON source, maps it to a C# model, and uses that collection as the grid data source. This approach is useful when application data originates from JSON files, APIs, configuration sources, or external services that return JSON payloads.

## Features

- Uses the Syncfusion Blazor DataGrid (`SfGrid`) to display JSON-backed records.
- Binds a strongly typed collection generated from JSON data to the grid data source.
- Demonstrates mapping JSON properties to a C# model defined in `GridData.cs`.
- Renders model fields through grid column definitions in the page hosting the DataGrid.
- Loads and processes data stored in `bind-data.json` before assigning it to the grid.

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## How to run the project

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`BindJsonObject.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd Blazor-DataGrid-Bind-JSON-Object
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Project structure

- `Pages/` — contains the Razor page that renders the Syncfusion Blazor DataGrid and performs JSON data binding.
- `GridData.cs` — defines the model used to deserialize and represent the JSON records displayed in the grid.
- `bind-data.json` — JSON data source consumed by the sample.

## Support and feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Refer to the Syncfusion Blazor DataGrid documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/data-binding/data-binding

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
