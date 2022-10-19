# R5T.NG0009
ASP.NET Core (Web library) framework selector library.

Note: .NET 6.0 is required.


## How To

Add a FrameworkReference:

    <Project Sdk="Microsoft.NET.Sdk">

      <PropertyGroup>
        <TargetFramework>net6.0</TargetFramework>
      </PropertyGroup>

      <ItemGroup>
        <FrameworkReference Include="Microsoft.AspNetCore.App" />
      </ItemGroup>

    </Project>

[Source](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/target-aspnetcore?view=aspnetcore-6.0&tabs=visual-studio#use-the-aspnet-core-shared-framework)