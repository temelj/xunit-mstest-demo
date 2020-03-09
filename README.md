# xunit-mstest-demo

This project is used to demonstrate that the latest Microsoft.NET.Test.Sdk (16.5.0) does not work well with .NET Core 2.1 & 2.2.

All projects are targeting the .NET Core 2.2 Framework.

> See Reported Issue: https://github.com/microsoft/vstest-docs/issues/225
> Also commented on the following: https://github.com/xunit/visualstudio.xunit/issues/200

## XUnit-2.4-NetTestSdk-16.2
This test runs the assert correctly and generates the appropriate test result.

## XUnit-2.4-NetTestSdk-16.5
This test never executes.

## Nuget Package for Microsoft.NET.Test.Sdk 16.5
https://www.nuget.org/packages/Microsoft.NET.Test.Sdk/16.5.0

This states depencency with
 .NETCoreApp 2.1
Microsoft.CodeCoverage (>= 16.5.0)
Microsoft.TestPlatform.TestHost (>= 16.5.0)

Therefore, one could assume compatibility with .NET Core 2.1+
