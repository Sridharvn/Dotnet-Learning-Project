# Setting Up Dotnet in MacBook

Macbook Air is famous for it's low amount of inbuilt storage space. Installing a big app such as Visual Studio in such a system is something that can't be done easily. Thus, we use Dotnet CLI along with VSCode to build a Dotnet app in the Macbook

### Installing Dotnet CLI in a Macbook

Multiple methods are available for installing Dotnet SDK and CLI in a macbook. The simplest and easiest way was using HomeBrew. A CLI based installlation tool for MaBook that can be used as an alternate for WinGet or Chocolatey for windows.

To install DotNet using HomeBrew, we use the command

```zsh
brew install --cask dotnet-sdk
```

This will install DotNet CLI and DotNet SDK to the MacBook.

# Creating new Dotnet Project using CLI

Creating a new project in DotNet using DotNet CLI is an interesting process.

To Create a Dotnet Project using CLI, we use the command

```zsh
dotnet new <template-name>
```

The command should be provided with a template for the type of DotNet project that has to be created

# Creating a Blazor Server App

Now we can create a Blazor Server App using DotNet

For that, we create a folder for the DotNet project to be in and in that folder, we provide command

```zsh
dotnet new blazorserver
```
