---
title: "NSwag"
ring: trial
quadrant: languages-and-frameworks
tags: ["library","REST API"]
--- 
NSwag is a Swagger/OpenAPI 2.0 and 3.0 toolchain for .NET, .NET Core, Web API, ASP.NET Core, TypeScript (jQuery, AngularJS, Angular 2+, Aurelia, KnockoutJS and more) and other platforms, written in C#. The OpenAPI/Swagger specification uses JSON and JSON Schema to describe a RESTful web API. The NSwag project provides tools to generate OpenAPI specifications from existing ASP.NET Web API controllers and client code from these OpenAPI specifications.

The project combines the functionality of Swashbuckle (OpenAPI/Swagger generation) and AutoRest (client generation) in one toolchain (these two libs are not needed). This way a lot of incompatibilites can be avoided and features which are not well described by the OpenAPI specification or JSON Schema are better supported (e.g. inheritance, enum and reference handling). The NSwag project heavily uses NJsonSchema for .NET for JSON Schema handling and C#/TypeScript class/interface generation.

- Documentation: https://github.com/RicoSuter/NSwag/wiki
- Source: https://github.com/RicoSuter/NSwag
- NuGet: https://www.nuget.org/packages/NSwag.AspNetCore
