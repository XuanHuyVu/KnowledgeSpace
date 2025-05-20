# Introduction
KnowledgeSpace is a open source project for everyone to learn and share knowledge. It is a knowledge management tool that allows users to create, organize, and share their knowledge in a structured way. It is built using Python and Flask, and uses SQLite as the database.

# Technologies stack
- ASP.NET Core 9.0
- Angular 19.0
- SQL Server 2022
- Identity Server 5.0

# How to run the project
1. Clone this repository to your local machine.
2. Open the project in your favorite IDE (e.g., Visual Studio, Visual Studio Code).
3. Build solution to restore all Nuget packages and dependencies.
4. Set startup project is KnowledgeSpace.BackendServer
5. Run Update-Database to generate the database.
6. Set Startup project to multiple projects include:
- KnowledgeSpace.BackendServer
- KnowledgeSpace.WebPortal
- KnowledgeSpace.ViewModels

# References
- [ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-7.0)
- [Angular](https://angular.dev/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [Identity Server](https://identityserver.io/)