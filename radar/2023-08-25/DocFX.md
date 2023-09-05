---
title: "DocFX"
ring: adopt
quadrant: tools
tags: ["documentation"]
--- 
Docfx is a powerful tool but easy to use for most regular use cases, once you understand the basic concepts.

Docfx can be used as a static site generator, but the real value of the tool is in bringing together static documentation pages and .NET API documentation. Docfx supports both C# and VB projects (although currently the output of tool is limited to C# syntax), and relies on the long-established XML comment syntax for C# (and similarly for VB).

Static documentation pages are prepared using Markdown (slightly enhanced to support specific features). Markdown content can also be injected into the generated API documentation using a feature called 'Overwrites'.

Once the API documentation has been parsed from the source code, it is compiled along with the Markdown content into a set of HTML pages which can be published on a website. It is also possible to compile the final output into one or more PDFs for offline use.

- Documentation: https://dotnet.github.io/docfx/
- Source: https://github.com/dotnet/docfx
- NuGet: https://www.nuget.org/packages/docfx (.NET tool)
