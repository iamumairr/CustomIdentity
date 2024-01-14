# Project Setup Guide

To run this project on your system, ensure that you have the following prerequisites installed:

1. **Visual Studio 2022 or Visual Studio Code**
2. **.NET 8 SDK**
3. **SQL Server (Preferred)** - You can use any other database, but ensure that you have the correct connection string.

## Steps to Set Up the Project:

### 1. Install Required Tools

- Install [Visual Studio 2022](https://visualstudio.microsoft.com/downloads) or [Visual Studio Code](https://code.visualstudio.com/).
- Install [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0).

### 2. Configure Database Connection

- Make changes to the connection string in the `AppSettings.json` file.

### 3. Run Migration Command

#### Using Visual Studio:
1. Navigate to **Tools** => **NuGet Package Manager** => **Package Manager Console**.
2. Run the following command: `update-database`.

#### Using Visual Studio Code:
1. Open the terminal.
2. Run the following command: `dotnet ef database update`.

## Additional Notes:

- Ensure that your SQL Server is up and running before executing the migration command.
- Double-check the connection string in `AppSettings.json` to avoid any connection issues.

With these steps completed, your project should be ready to run. If you encounter any issues during setup, refer to the project contributors.
