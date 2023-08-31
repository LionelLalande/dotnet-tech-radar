---
title: "FakeItEasy"
ring: trial
quadrant: languages-and-frameworks 
featured: true
tags: ["library","testing","mock, fakes & stubs"]
--- 
FakeItEasy is an open-source .NET library that helps you create mock objects and stubs for testing purposes. Mocking frameworks like FakeItEasy are used in unit testing to isolate the code being tested from its dependencies, allowing you to focus on testing individual components in isolation.

Key features and concepts of FakeItEasy include:

## Mocking: 
FakeItEasy allows you to create mock objects that simulate the behavior of real objects. These mocks can be configured to behave in specific ways during tests.

## Stubs: 
Stubs are objects that provide pre-defined responses to method calls. They are useful for isolating the code being tested from its dependencies.

## Arrange-Act-Assert (AAA) Pattern: 
FakeItEasy promotes the AAA pattern for unit testing. This involves arranging the test by setting up the mock's behavior, acting by invoking the code under test, and then asserting the expected outcomes.

## Fluent Interface: 
FakeItEasy provides a fluent and expressive API for setting up mock behaviors and expectations.

## Method Call Verification: 
You can use FakeItEasy to verify that specific methods were called with the expected arguments during a test.

## Argument Matchers: 
FakeItEasy allows you to use argument matchers to specify conditions for method calls, such as specific argument values or ranges.

## Configurable Return Values: 
You can configure mock methods to return specific values or execute specific actions when they are called.

## Exception Throwing: 
FakeItEasy lets you configure mock methods to throw exceptions when certain conditions are met, helping you test error handling scenarios.

## Integration with Testing Frameworks: 
FakeItEasy integrates with popular .NET testing frameworks like NUnit, xUnit, and MSTest.

## NuGet Package: 
FakeItEasy is available as a NuGet package, making it easy to add to your .NET projects
