
```
dotnet new classlib --name ClassLib1
dotnet new classlib --name ClassLib2
dotnet new sln --name StyleCopDemo
dotnet sln add .\StyleCopDemo.sln .\ClassLib1\ClassLib1.csproj
dotnet sln add .\StyleCopDemo.sln .\ClassLib2\ClassLib2.csproj
```
