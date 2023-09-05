---
title: "Verify"
ring: adopt
quadrant: languages-and-frameworks
tags: ["library","testing","snapshotting"]
--- 
Verify is a snapshot tool that simplifies the assertion of complex data models and documents.

Verify is called on the test result during the assertion phase. It serializes that result and stores it in a file that matches the test name. On the next test execution, the result is again serialized and compared to the existing file. The test will fail if the two snapshots do not match: either the change is unexpected, or the reference snapshot needs to be updated to the new result.

- Source: https://github.com/VerifyTests/Verify
- NuGet: https://www.nuget.org/packages/Verify
