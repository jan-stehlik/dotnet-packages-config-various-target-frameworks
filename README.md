This is an example .NET app that has dependencies managed by `packages.config` and uses multiple target frameworks.

## Getting started

Prerequisites:

- [.NET](https://dotnet.microsoft.com/download) installed

### Build

```bash
dotnet build
```

### Run the app

```bash
dotnet run
```

### Restore dependencies

This will create `project.assets.json` in obj folder with a depenedency tree.

```bash
dotnet restore
```
