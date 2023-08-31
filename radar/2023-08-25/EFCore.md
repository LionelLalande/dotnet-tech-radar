---
title: "EF Core"
ring: adopt
quadrant: languages-and-frameworks 
featured: true
tags: ["framework","ORM"]
--- 
Entity Framework Core (EF Core) is an open-source, lightweight, and cross-platform version of Entity Framework, designed specifically for .NET Core and .NET 5+ applications. Similar to Entity Framework, EF Core is an object-relational mapping (ORM) framework that enables developers to work with databases using .NET objects and queries, while providing improved performance and flexibility.

Key features and concepts of Entity Framework Core include:

-Cross-Platform Support: EF Core is designed to work on different platforms, including Windows, Linux, and macOS. It's tightly integrated with .NET Core and .NET 5+.

-Code-First Approach: Like EF, EF Core supports the code-first approach, allowing you to define your domain model using .NET classes and attributes. The database schema can be generated from these classes.

-Database-First Approach: EF Core also supports the database-first approach, where you start with an existing database and generate .NET classes that correspond to database tables.

-LINQ and Querying: EF Core supports LINQ queries, allowing you to express database queries using .NET code. LINQ queries are translated into SQL queries by EF Core.

-DbContext: Similar to EF, EF Core uses the DbContext class to manage interactions with the database. DbContext is the entry point to define and manage entities, relationships, and database operations.

-Migrations: EF Core includes a migrations system that enables you to evolve the database schema over time while preserving data.

-Database Providers: EF Core supports various database providers, including SQL Server, MySQL, PostgreSQL, SQLite, and more. Each provider has its own NuGet package and configuration options.

-In-Memory Database: EF Core offers an in-memory database provider that's useful for testing scenarios and fast prototyping without needing a physical database.

-Entity States and Change Tracking: EF Core tracks the states of entities and their changes automatically, simplifying the process of updating and persisting data.

-Lazy Loading and Eager Loading: EF Core supports both lazy loading and eager loading of related entities.

-Concurrency Control: EF Core provides mechanisms for handling concurrent data updates, such as optimistic concurrency control.

-Dependency Injection: EF Core is designed with dependency injection in mind and integrates seamlessly with ASP.NET Core's built-in dependency injection container.

-Logging and Diagnostics: EF Core provides logging and diagnostics options to help you monitor and troubleshoot database interactions.
