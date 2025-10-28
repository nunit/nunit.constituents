# Information on other projects that uses NUnit as a library or tool

This is a list of projects that use NUnit as a library or tool. If you have a project that uses NUnit and would like to add it to this list, please submit a pull request.

We will use this list to reach out to these constituents to inform them of the upcoming releases, possibly changes that may affect them, and to solicit feedback.

This is to avoid breaking changes and to ensure that we are not breaking any existing projects that depend on NUnit.

| Project Name | Source repo |Downloads | Usage of NUnit[^1] | NUnit version  |   Maintainer(s) or Contact(s) |
|--------------|-------------|-----------|---------------|--------|-------|
|FluentAssertions|[Github](https://www.nuget.org/packages/FluentAssertions)|![NuGet Downloads](https://img.shields.io/nuget/dt/FluentAssertions)||3.14.0, 4.1.0|[Dennis Doomen](https://github.com/dennisdoomen)|
|SpecFlow.NUnit|[Github](https://www.nuget.org/packages/SpecFlow.NUnit/)|![NuGet Downloads](https://img.shields.io/nuget/dt/Specflow.Nunit)||||
|Xamarin.UITest|Closed source|![NuGet Downloads](https://img.shields.io/nuget/dt/Xamarin.UITest)|||Microsoft|
|Verify|[Github](https://github.com/VerifyTests/Verify)|![NuGet Downloads](https://img.shields.io/nuget/dt/Verify)|||[Simon Cropp](https://github.com/SimonCropp)|
|AutoFixture.NUnit3|[Github](https://github.com/AutoFixture/AutoFixture)|![NuGet Downloads](https://img.shields.io/nuget/dt/AutoFixture.NUnit3)||3.7.0, 4.0.0|[Mark Seemann](https://github.com/ploeh)|
|Microsoft.Playwright.NUnit|[Github](https://github.com/microsoft/playwright-dotnet)|![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.Playwright.NUnit)|||Microsoft|
|Akka.TestKit|[Github](https://github.com/akkadotnet/akka.net)|![NuGet Downloads](https://img.shields.io/nuget/dt/Akka.TestKit)||||
|AwesomeAssertions|[Github](https://github.com/AwesomeAssertions/AwesomeAssertions)|![NuGet Downloads](https://img.shields.io/nuget/dt/AwesomeAssertions)|||[Christoph Bersch](https://github.com/cbersch)|

[!NOTE]
This list should contain only highly used projects. If you are not sure, please reach out to the NUnit team for guidance.


[^1]: What part of NUnit is being used. We have a public interface and api that is meant to be used by others, but we observe some projects also use parts of our internal code. This is important to know when we make changes to our codebase.  So we use keywords `api` and `internal` to indicate this.