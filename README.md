# net-core-get-started
A set of links and instructions that i gather while starting my first .net core project, i want to be able to work with or without Visual Studio

## Prerequisites
1. [Instalation instructions for any OS](https://www.microsoft.com/net/core#windows)
2. Windows Specific for Visual Studio: [Visual Studio official MSI Installer](https://go.microsoft.com/fwlink/?LinkId=798481), [NuGet Manager extension for Visual Studio](https://dist.nuget.org/visualstudio-2015-vsix/v3.5.0-beta/NuGet.Tools.vsix), 
3. Windows Speficif to work without Visual Studio: [.NET Core SDK for Windows](https://go.microsoft.com/fwlink/?LinkID=798398), [Nuget Command Line](https://dist.nuget.org/index.html)(You need to download the nuget.exe and place it in a location of yout PATH so that you can use it from the command line)

## Creating a first project:
#### With Visual Studio  
File -> Visual C# -> New project -> .Net Core
![screenshot_12](https://cloud.githubusercontent.com/assets/4844997/15785173/1cd055fc-2973-11e6-8311-4b98eb81ff00.png)

### Without Visual Studio
From the command line  create and empty directory and go in then:
```bash
dotnet new
dotnet restore
```   
Note: That dotnet new creates a console application, for creating a web application you can check [here](https://docs.asp.net/en/1.0.0-rc2/getting-started.html) and to create a class library project you can check [here](http://stackoverflow.com/a/37620232/1685147)
