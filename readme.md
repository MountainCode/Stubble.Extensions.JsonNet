# Json.Net Stubble Extensions [![Build status](https://img.shields.io/appveyor/ci/Romanx/stubble-extensions-jsonnet.svg?style=flat-square)](https://ci.appveyor.com/project/Romanx/stubble-extensions-jsonnet) [![Build Status](https://travis-ci.org/StubbleOrg/Stubble.Extensions.JsonNet.svg?branch=master)](https://travis-ci.org/StubbleOrg/Stubble.Extensions.JsonNet) [![codecov](https://codecov.io/gh/StubbleOrg/Stubble.Extensions.JsonNet/branch/master/graph/badge.svg)](https://codecov.io/gh/StubbleOrg/Stubble.Extensions.JsonNet) [![Prerelease Nuget](https://img.shields.io/nuget/vpre/Stubble.Extensions.JsonNet.svg?style=flat-square&label=nuget%20pre)](https://www.nuget.org/packages/Stubble.Extensions.JsonNet/) [![Stable Nuget](https://img.shields.io/nuget/v/Stubble.Extensions.JsonNet.svg?style=flat-square)](https://www.nuget.org/packages/Stubble.Extensions.JsonNet/)

<img align="right" width="160px" height="160px" src="https://raw.githubusercontent.com/StubbleOrg/Stubble/dev/assets/extension-logo-256.png">

This repository contains easy to use extensions for interacting with Newtonsoft Json.Net.

To use this just include it in your project by downloading the dll from the release section,
or preferably including it from Nuget.org through the badge above.

Example Usage:
```csharp
var builder = new StubbleBuilder().Configure(settings => settings.AddJsonNet()).Build();
```

It's as simple as that, the package contains an Extension method for the StubbleBuilder adding
in the ValueGetters required to handle JTokens.

## Compilation
Currently this does not contain ValueGetters that work with compilation.
If there is a demand for this however we will consider adding another package or add the dependency to this package.

## Credits

Straight Razor by Vectors Market from the Noun Project