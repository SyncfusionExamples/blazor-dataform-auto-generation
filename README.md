# Blazor DataForm Auto-generation

A sample Blazor application demonstrating automatic form generation using the [DataForm](https://www.syncfusion.com/blazor-components/blazor-data-form) component. This project showcases how to leverage data model properties and validation attributes to automatically generate responsive input fields without manual markup.

## Overview

This repository demonstrates the power of the `SfDataForm` component combined with `FormAutoGenerateItems` for creating data-driven forms. The sample includes validation, data annotations, and display customization—all generated automatically from your model definitions.

## Features
- Automatic form field generation from model properties
- Built-in validation using `DataAnnotationsValidator`
- Custom display options (column spanning, spacing, formatting)
- Date field constraints and formatting
- Responsive grid layout with configurable columns
- Type-safe model binding with Blazor interoperability

## Prerequisites

* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)
* [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-dataform-auto-generation.git
cd blazor-dataform-auto-generation
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run 
```

## Resources

- [Blazor DataForm Documentation](https://blazor.syncfusion.com/documentation/data-form/getting-started/)
- [Blazor DataForm Demo](https://blazor.syncfusion.com/demos/data-form/default-functionalities?theme=fluent2)

