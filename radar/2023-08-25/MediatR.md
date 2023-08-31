---
title: "MediatR"
ring: assess
quadrant: languages-and-frameworks 
featured: true
tags: ["library","bus","CQRS"]
--- 
MediatR is an open-source .NET library that provides a simple and lightweight implementation of the mediator pattern. The mediator pattern is a behavioral design pattern that promotes loose coupling between components by centralizing communication between them through a mediator object. MediatR simplifies the implementation of this pattern, making it easier to manage communication between different parts of an application.

Key features and concepts of MediatR include:

## Mediator Pattern: 
MediatR helps implement the mediator pattern, where components (handlers) communicate through a central mediator without directly referencing each other.

## Request and Response Handling: 
MediatR facilitates the handling of requests and responses between different parts of your application. Requests can represent commands, queries, or other actions.

## Request Handlers: 
Handlers are responsible for processing incoming requests. Each request type has its corresponding handler.

## Notification Handlers: 
In addition to requests and responses, MediatR also supports notifications. Notification handlers can perform actions in response to notifications being raised.

## Decoupling: 
MediatR promotes decoupling between components, making it easier to change and extend your application without affecting other parts.

## Pipeline Behavior: 
MediatR allows you to define behaviors that can intercept and modify the processing of requests and responses. This is useful for tasks like validation, logging, and authorization.

## Asynchronous Processing: 
Handlers and behaviors can be asynchronous, which is important for optimizing the responsiveness of your application.

## Integration with Dependency Injection: 
MediatR integrates well with dependency injection containers like Microsoft.Extensions.DependencyInjection.

## Usage with Command and Query Responsibility Segregation (CQRS): 
MediatR is commonly used in combination with CQRS architectural patterns to separate command and query responsibilities.

## NuGet Package: 
MediatR is available as a NuGet package, making it easy to integrate into your .NET projects.
