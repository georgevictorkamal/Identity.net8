# ASP.NET Identity using .NET 8 Readme

## Introduction
This project is a simple and clear demonstration of how to implement ASP.NET Identity using .NET 8. ASP.NET Identity is the membership system for building ASP.NET web applications, including creating users, verifying user credentials, and managing roles.

## Prerequisites
- .NET 8 SDK
- Visual Studio 2019 or 2022
- SQL Server

## Setup

1. Clone the repository
git clone https://github.com/georgevictorkamal/Identity.net8.git

2. Navigate into the project directory
cd yourrepository

3. Restore the required packages
dotnet restore

4. Update the database connection string in `appsettings.json`.

5. Run the migration to create the database schema
dotnet ef database update

6. Run the project
dotnet run


## Project Structure
- `Controllers` - Contains all the API controllers.
- `Models` - Contains all the models used in the project.
- `Data` - Contains the application DB context and the migrations.
- `Services` - Contains the services used for business logic and data manipulation.
- `wwwroot` - Contains the static files for the frontend part.

## Usage
Once the application is running, you can navigate to `https://localhost:5001` to view the application in your web browser.

## Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
