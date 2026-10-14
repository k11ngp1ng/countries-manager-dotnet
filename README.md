# Countries, States, and Cities Manager

C# desktop application for managing and querying countries, states, and cities, featuring clear separation between entities, controllers, and data access layers.

## Objective
Practice object-oriented desktop development concepts and data persistence in a domain with hierarchical relationships.

## Features
- Registration of countries, states, and cities
- Querying registered entities
- Screen navigation powered by Windows Forms
- Data access operations organized via Data Access Object (DAO) pattern
- Separation of concerns among entities, controllers, and forms

## Technologies
- C#
- Windows Forms
- .NET
- SQL

## Architecture

| Component | Responsibility |
| :--- | :--- |
| `Paises.cs`, `Estados.cs`, `Cidades.cs` | Domain entities |
| `CtrlPaises.cs`, `CtrlEstados.cs`, `CtrlCidades.cs` | Control rules and orchestration |
| `DaoPaises.cs`, `DaoEstados.cs`, `DaoCidades.cs` | Data access layer |
| `Frm*.cs` | Registration and query user interfaces |
| `SQLQuery*.sql` | Project SQL scripts |

## How to Run

1. Open `ProjetoElp4Paises.sln` in Visual Studio.
2. Configure the database connection according to the configuration file and SQL scripts in the repository.
3. Build and run the project through the IDE.

## Key Learnings
- Modeling relationships between entities.
- Implementing layered architecture for desktop applications.
- Building CRUD and query user interfaces with Windows Forms.
- Integrating a C# application with a relational database.

## Next Steps
- Centralize connection configuration using environment variables.
- Add more detailed input validations and error handling.
- Write unit and integration tests for business logic and data access.
