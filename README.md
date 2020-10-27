# AndcultureCode.CSharp.Data [![Build Status](https://travis-ci.org/AndcultureCode/AndcultureCode.CSharp.Data.svg?branch=master)](https://travis-ci.org/AndcultureCode/AndcultureCode.CSharp.Data) [![codecov](https://codecov.io/gh/AndcultureCode/AndcultureCode.CSharp.Data/branch/master/graph/badge.svg)](https://codecov.io/gh/AndcultureCode/AndcultureCode.CSharp.Data)
Infrastructure layer's general purpose data actors

From this package, specific storage mechanisms will have their own 'data' package (ie. `AndcultureCode.CSharp.Data.SqlServer`)

## Getting Started
This package is installed via NuGet
```
dotnet add [<PROJECT>] package AndcultureCode.CSharp.Data
```

## Documentation

[Full API Documentation](src/AndcultureCode.CSharp.Data/AndcultureCode.CSharp.Data.md)


## Development Setup

* Install Dotnet Core 2.x
* Install the `and-cli` tooling found at [AndcultureCode.Cli](https://github.com/AndcultureCode/AndcultureCode.Cli)

Below are a few basics to get you started, but there are many more commands and options for managing this and other projects found in the `and-cli`.

### Building project
* Run the build command
    ```
    and-cli dotnet --build
    ```

### Running tests along with code coverage
* Run the test command
    ```
    and-cli dotnet-test
    ```
* Open the `coverage/index.htm` file in your browser

### Publishing a new version
* Run the publish command with the next version number ([See semver package versioning](https://docs.microsoft.com/en-us/nuget/concepts/package-versioning))
    ```
    and-cli nuget --publish <version>
    ```

# Community

[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/0)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/0)[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/1)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/1)[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/2)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/2)[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/3)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/3)[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/4)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/4)[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/5)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/5)[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/6)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/6)[![](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/images/7)](https://sourcerer.io/fame/andCulture/AndcultureCode/AndcultureCode.CSharp.Data/links/7)

Contributing
======

Information on contributing to this repo is in the [Contributing Guide](CONTRIBUTING.md)
