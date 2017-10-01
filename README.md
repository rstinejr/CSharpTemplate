# CSharpTemplate
Directory structure for a .NET Core project with xUnit tests.

Created with dotnet 2.0.

To download .NET Core, see https://dot.net


To build and run from the command line:

1. ```pushd MyProject```
2. ```dotnet restore```
3. ```dotnet build```
4. ```dotnet run```
5. ```popd```

To build tests and run them from the command line
1. ```pushd test```
2. ```dotnet restore```
3. ```dotnet build```
4. ```dotnet test```
5. ```popd```

Alternatively, if on Windows, use the Visual Studio solution file to build the project and run the test.

Build on 64-bit Windows 10, with .NET Core, dotnet 2.0, VisualStudio 15.3.
