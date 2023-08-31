---
title: "Polly"
ring: adopt
quadrant: languages-and-frameworks 
featured: true
tags: ["library","resilience"]
--- 
Polly is an open-source .NET library that provides resilience and transient-fault handling capabilities for applications. It helps developers build robust and reliable applications by providing mechanisms to handle faults and retries when interacting with external services or resources.

Key features and concepts of Polly include:

## Resilience Policies: 
Polly offers a set of predefined policies, such as Retry, Circuit Breaker, Timeout, and Bulkhead Isolation, which handle common transient faults and improve the stability of your application.

## Fluent API: 
Polly provides a fluent and expressive API that allows you to configure and apply resilience policies to various operations.

## Retry Policies: 
Retry policies enable you to automatically retry failed operations a specified number of times, with configurable wait times between retries.

## Circuit Breaker Policies: 
Circuit breakers help prevent the repeated execution of failing operations by temporarily opening the circuit when a certain failure threshold is reached.

## Timeout Policies: 
Timeout policies ensure that an operation is canceled if it takes longer than a specified duration to complete.

## Bulkhead Isolation Policies: 
Bulkhead isolation policies limit the number of concurrent executions of a specific operation, preventing resource exhaustion.

## Fallback Policies: 
Polly supports fallback policies that define alternative behavior or default values when an operation fails.

## Policy Composition: 
You can compose multiple policies to create complex resilience strategies for different scenarios.

## Asynchronous and Synchronous: 
Polly supports both synchronous and asynchronous operations, making it suitable for various types of applications.

## Integration with HttpClient: 
Polly integrates seamlessly with HttpClient, enabling automatic retry and fault handling for HTTP requests.

Custom Policies: 
You can create custom resilience policies that cater to your specific application needs.

## Integration with DI Containers: 
Polly integrates well with popular dependency injection (DI) containers, such as Microsoft.Extensions.DependencyInjection.
