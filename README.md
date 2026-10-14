# Getting Started with the Syncfusion Blazor Splitter Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Splitter](https://www.syncfusion.com/blazor-components/blazor-splitter) in a Blazor WebAssembly hosted application. The application uses a horizontal splitter layout with multiple panes, including a nested vertical splitter and integrated tabbed content. The sample shows how to create flexible dashboard-style interfaces by combining resizable and collapsible panes with other Syncfusion components.

## Key Features

- Uses the `SfSplitter` component to create a multi-pane layout.
- Configures horizontal and nested vertical splitter layouts using the `Orientation` property.
- Defines pane sizes using the `Size` property.
- Supports pane collapse and expand functionality using the `Collapsible` and `Collapsed` properties.
- Prevents resizing of specific panes using the `Resizable` property.
- Renders pane content using the `Content` property and `ContentTemplate`.
- Integrates the `SfTab` component within a splitter pane.
- Displays multiple tab views using `TabItems`, `TabItem`, and `TabHeader`.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Clone the repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the startup project directory for the hosted application.

```bash
dotnet restore
dotnet run
```

5. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.

- `Client/Pages/Index.razor` — Main sample page demonstrating the Syncfusion Splitter component with nested splitter layouts and tab integration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/splitter/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.