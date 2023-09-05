---
title: "FsCheck"
ring: adopt
quadrant: languages-and-frameworks
tags: ["library","testing","property testing","random testing"]
--- 
FsCheck is a tool for testing .NET programs automatically. The programmer provides a specification of the program, in the form of properties which functions, methods or objects should satisfy, and FsCheck then tests that the properties hold in a large number of randomly generated cases. While writing the properties, you are actually writing a testable specification of your program. Specifications are expressed in F#, C# or VB, using combinators defined in the FsCheck library. FsCheck provides combinators to define properties, observe the distribution of test data, and define test data generators. When a property fails, FsCheck automatically displays a minimal counter example.

- Documentation: https://fscheck.github.io/FsCheck/
- Source: https://github.com/fscheck/FsCheck
- NuGet: https://www.nuget.org/packages/FsCheck
