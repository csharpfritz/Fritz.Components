# Fritz.Components

A Blazor component library featuring useful components like EnvironmentRibbon.

## Installation

```
dotnet add package Fritz.Components
```

## Usage

### Environment Ribbon

The Environment Ribbon component displays the current environment name with configurable styling:

```razor
<EnvironmentRibbon HideInProduction="true" />
```

This will show a colored ribbon with the environment name except in Production (by default).