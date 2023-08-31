---
title: "Dapper"
ring: adopt
quadrant: languages-and-frameworks 
featured: true
tags: ["library","ORM"]
--- 
Dapper is an open-source, lightweight, and high-performance micro-ORM (Object-Relational Mapping) library for .NET. It simplifies database access by providing a simple and efficient way to query and map data from relational databases to .NET objects, while avoiding the complexities and overhead of full-fledged ORMs.

Key features and concepts of Dapper include:

-Performance: Dapper is designed for high performance and minimal overhead. It uses raw ADO.NET underneath but abstracts away much of the boilerplate code required for data retrieval and mapping.

-SQL Query Mapping: Dapper allows you to write SQL queries directly and map the results to strongly typed objects. It provides methods like Query, QueryFirstOrDefault, and more to retrieve data from the database.

-Parameterized Queries: Dapper supports parameterized queries, helping to prevent SQL injection vulnerabilities and improve query execution efficiency.

-Automatic Mapping: Dapper automatically maps the results of your queries to .NET objects using reflection. You can also use custom mapping logic to control how data is mapped.

-Stored Procedures: Dapper supports calling stored procedures by providing methods like Query and Execute to work with stored procedures.

-Multi-Mapping: Dapper supports querying for data and mapping it to multiple related objects. This is useful for retrieving hierarchical or joined data.

-Asynchronous Operations: Dapper offers asynchronous methods, allowing you to perform database operations without blocking the calling thread.

-Connection Management: Dapper simplifies the management of database connections and the execution of commands.

NuGet Package: Dapper is available as a NuGet package, making it easy to integrate into your .NET projects.
