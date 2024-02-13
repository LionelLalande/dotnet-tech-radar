---
title: "Mapperly"
ring: adopt
quadrant: languages-and-frameworks
tags: ["library","mapping"]
---

Mapperly is a .NET source generator for generating object mappings. It drastically simplifies the implementation of object to object mappings. One only needs to define the mapping methods signature. The implementation is provided by Mapperly.

Because Mapperly creates the mapping code at build time, there is minimal overhead at runtime. Even better, the generated code is perfectly readable, allowing you to verify the generated mapping code easily.

Mapperly works by using .NET Source Generators. Since no reflection is used at runtime, the generated code is completely trimming safe and AoT friendly.

Mapperly was originally inspired by MapStruct.

- Documentation: https://mapperly.riok.app/docs/intro/
- Source: https://github.com/riok/mapperly
- NuGet: https://www.nuget.org/packages/Riok.Mapperly
