<p align="center"><img src="../assets/icon.png"/></p>

<h1 align="center">MSEssentials</h1>

<h3 align="center"><b>Set of helpers, class extensions, UI controls used in my other C# projects</b></h3>

<p align="center">MSEssentials is package of useful classes, helpers, extensions and UI controls, I use in my C# projects.</p>

---

## Informations

> [!Important]
> This organization and repositories are only mirror to <a href="https://repos.mateuszskoczek.com/MSEssentials">this</a>. All changes are first uploaded to the original repositories. Releases are also published on original repositories. However, Github repositories handles issues and pull requests for better accessibility.

## List of subpackages

<table>
    <tr>
        <th>
            Subpackage
        </th>
        <th>
            Description
        </th>
        <th>
            Repository URL
        </th>
        <th>
            NuGet registry status
        </th>
    </tr>
    <tr>
        <th>
            MSEssentials.Extensions
        </th>
        <td>
            Class extensions
        </td>
        <td>
            <a href="https://repos.mateuszskoczek.com/MSEssentials/MSEssentials.Extensions"><img src="https://img.shields.io/badge/repository-darkgreen?style=flat-square&logo=gitea"/></a>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/MSEssentials.Extensions/"><img src="https://img.shields.io/nuget/v/MSEssentials.Extensions.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <th>
            MSEssentials.Attributes
        </th>
        <td>
            Class, method and property attributes
        </td>
        <td>
            <a href="https://repos.mateuszskoczek.com/MSEssentials/MSEssentials.Attributes"><img src="https://img.shields.io/badge/repository-darkgreen?style=flat-square&logo=gitea"/></a>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/MSEssentials.Attributes/"><img src="https://img.shields.io/nuget/v/MSEssentials.Attributes.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <th>
            MSEssentials.UI.Common.MVVM
        </th>
        <td>
            MVVM architecture models and helper classes
        </td>
        <td>
            <a href="https://repos.mateuszskoczek.com/MSEssentials/MSEssentials.UI.Common.MVVM"><img src="https://img.shields.io/badge/repository-darkgreen?style=flat-square&logo=gitea"/></a>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/MSEssentials.UI.Common.MVVM/"><img src="https://img.shields.io/nuget/v/MSEssentials.UI.Common.MVVM.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <th>
            MSEssentials.UI.Common.Converters
        </th>
        <td>
            Base for UI framework-specific XAML converters
        </td>
        <td>
            <a href="https://repos.mateuszskoczek.com/MSEssentials/MSEssentials.UI.Common.Converters"><img src="https://img.shields.io/badge/repository-darkgreen?style=flat-square&logo=gitea"/></a>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/MSEssentials.UI.Common.Converters/"><img src="https://img.shields.io/nuget/v/MSEssentials.UI.Common.Converters.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <th>
            MSEssentials.UI.WinUI.Behaviors
        </th>
        <td>
            XAML action triggers for WinUI applications
        </td>
        <td>
            <a href="https://repos.mateuszskoczek.com/MSEssentials/MSEssentials.UI.WinUI.Behaviors"><img src="https://img.shields.io/badge/repository-darkgreen?style=flat-square&logo=gitea"/></a>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/MSEssentials.UI.WinUI.Behaviors/"><img src="https://img.shields.io/nuget/v/MSEssentials.UI.WinUI.Behaviors.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <th>
            MSEssentials.UI.WinUI.Converters
        </th>
        <td>
            XAML value converters for WinUI applications
        </td>
        <td>
            <a href="https://repos.mateuszskoczek.com/MSEssentials/MSEssentials.UI.WinUI.Converters"><img src="https://img.shields.io/badge/repository-darkgreen?style=flat-square&logo=gitea"/></a>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/MSEssentials.UI.WinUI.Converters/"><img src="https://img.shields.io/nuget/v/MSEssentials.UI.WinUI.Converters.svg?style=flat-square"></a>
        </td>
    </tr>
    <tr>
        <th>
            MSEssentials.UI.WinUI.Controls
        </th>
        <td>
            Custom UI controls for WinUI applications
        </td>
        <td>
            <a href="https://repos.mateuszskoczek.com/MSEssentials/MSEssentials.UI.WinUI.Controls"><img src="https://img.shields.io/badge/repository-darkgreen?style=flat-square&logo=gitea"/></a>
        </td>
        <td>
            <a href="https://www.nuget.org/packages/MSEssentials.UI.WinUI.Controls/"><img src="https://img.shields.io/nuget/v/MSEssentials.UI.WinUI.Controls.svg?style=flat-square"></a>
        </td>
    </tr>
</table>

## Installation and usage

All subpackages can be download independently from official NuGet registry. You can also download .nupkg files from each repository Releases page.

**CLI:**

```
dotnet add package MSEssentials.<subpackage>
```

**Package reference in .csproj file:**

```
<PackageReference Include="MSEssentials.<subpackage>" Version="<version>" />
```

## Attribution and contribution

This project is open source on MIT License, so you can just copy and upload again to your repository. But according to the license, you must include information about the original author. You can find licenses in each repository's LICENSE files. 

However, the preferred way to contribute would be to propose improvements in a pull request, through issues, or through other means of communication.

**Other sources:**

- Icon by <a href="icons8.com">Icons8</a>