# Theater Project

## Overview

Theater Project is a Theater Management System built with ASP.NET Core MVC, C#, Entity Framework Core, and SQL Server.

The system allows users to manage movies, actors, cast members, theater places, and movie tracking operations through a clean MVC architecture.

## Features

* User login and authentication
* Manage movies (Add, Edit, Delete, View)
* Manage actors and cast members
* Manage theater places and locations
* Movie tracking system
* Image upload for movies and actors
* SQL Server database integration
* Entity Framework Core relationships

## Technologies Used

* ASP.NET Core MVC
* C#
* Entity Framework Core
* SQL Server
* Razor Views
* Cookie Authentication
* HTML / CSS / Bootstrap

## Project Structure

* **Models** → Database entities and relationships
* **Views** → User interface using Razor Pages
* **Controllers** → Business logic and request handling
* **wwwroot** → Static files and uploaded images
* **Program.cs** → Application startup and configuration

## Database

The project uses SQL Server with Entity Framework Core for data management.

Main tables include:

* Movies
* Actors
* Cast Members
* Theater Places
* Cities
* Districts
* Movie Tracking

## How to Run

1. Clone the repository
2. Open the project in Visual Studio
3. Configure the SQL Server connection string in `appsettings.json`
4. Restore NuGet packages
5. Run database migrations (if needed)
6. Start the project using IIS Express or `dotnet run`

## Purpose

This project was created to practice full-stack ASP.NET Core MVC development, database relationships, authentication, and CRUD operations in a real-world management system.

## Author

Cihat Brejavi
