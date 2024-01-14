For running the project in your system, you'll need

1. Visual Studio 2022 or Visual Studio Code
2. .Net 8 SDK
3. SQL Server (Preferred) - you can you any other DB, but make sure to have correct connection string

Make changes to connection string in AppSettings.json file, and run a migration command: 

1. Visual Studio => Tools => Nuget Package Manager => Package Manager Conslole => update-database OR
2. Visual Studio Code => terminal => dotnet ef database update
