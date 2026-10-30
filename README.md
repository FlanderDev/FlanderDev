<a href="https://flander.dev">
  <img src="assets/header.svg" alt="Felix 'FlanderDev' Leander: C# / .NET developer, game modder, tool builder" width="100%" />
</a>

<p align="center">
  <a href="https://flander.dev"><img src="https://img.shields.io/badge/flander.dev-0a0a0f?style=for-the-badge&logo=firefox&logoColor=FF2400" alt="Website" /></a>
  <a href="https://discordapp.com/users/536544797997924362"><img src="https://img.shields.io/badge/Discord-0a0a0f?style=for-the-badge&logo=discord&logoColor=47c8ff" alt="Discord" /></a>
  <a href="https://www.nuget.org/profiles/FlanderDev"><img src="https://img.shields.io/badge/NuGet-0a0a0f?style=for-the-badge&logo=nuget&logoColor=e8ff47" alt="NuGet" /></a>
  <img src="https://komarev.com/ghpvc/?username=FlanderDev&style=for-the-badge&color=0a0a0f&label=visitors" alt="Profile views" />
</p>

<p align="center"><b>Welcome, fellow nerds!</b> I'm Flan, an electrician-turned-software-engineer from Germany 🇩🇪<br/>
I mostly write <b>C#</b>, build stuff for games I play, and try (and fail) to avoid JavaScript.</p>

## 🧰 Toolbox
<p align="center">
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=cs,dotnet,kotlin,java,androidstudio,rust,godot,unity,blender&theme=dark" alt="Languages and engines" /></a>
  <br/>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=sqlite,docker,linux,githubactions,visualstudio,vscode,git,js&theme=dark" alt="Tools" /></a>
</p>

<p align="center"><sub>JavaScript is on the list under protest.</sub></p>

## 🛠️ What I'm building
<table>
<tr>
<td width="50%" valign="top">

### 🧩 [F3M](https://github.com/FlanderDev/F3M)
**A mod hub and mod manager for a BepInEx-modded Unity game.**<br/>
A website where authors upload mods and players browse them, plus a desktop app that installs mods with all their dependencies and removes them cleanly.

- Mod types, versioning, dependencies, optional files, tag voting
- **Signed catalog**, works offline, `f3m://` deep links
- Desktop app updates itself on Windows and Linux
- ~200 community mods imported and claimable by their authors

![Blazor](https://img.shields.io/badge/Blazor_WASM-512BD4?style=flat-square&logo=blazor&logoColor=white)
![Avalonia](https://img.shields.io/badge/Avalonia-8B44AC?style=flat-square&logo=avaloniaui&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core_+_SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
<br/>
[![Release](https://img.shields.io/github/v/release/FlanderDev/F3M?style=flat-square&label=release&color=e8ff47&labelColor=0a0a0f)](https://github.com/FlanderDev/F3M/releases/latest)
[![Stars](https://img.shields.io/github/stars/FlanderDev/F3M?style=flat-square&color=47c8ff&labelColor=0a0a0f)](https://github.com/FlanderDev/F3M/stargazers)

</td>
<td width="50%" valign="top">

### ⚡ [RouteGen](https://github.com/FlanderDev/RouteGen)
**A Roslyn source generator for hosted Blazor WebAssembly apps.**<br/>
Define your API once as a C# interface. RouteGen generates the rest:

- an abstract ASP.NET Core controller base (server)
- a strongly typed `HttpClient` implementation (client)
- typed page-route helpers from `@page` directives

One source of truth for routes, so URL strings can't drift out of sync. F3M runs on it.

![.NET 10](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Roslyn](https://img.shields.io/badge/Roslyn-239120?style=flat-square&logo=csharp&logoColor=white)
<br/>
[![NuGet](https://img.shields.io/nuget/v/FlanderDev.RouteGen.Generators?style=flat-square&label=nuget&color=e8ff47&labelColor=0a0a0f)](https://www.nuget.org/packages/FlanderDev.RouteGen.Generators)
[![Downloads](https://img.shields.io/nuget/dt/FlanderDev.RouteGen.Generators?style=flat-square&color=47c8ff&labelColor=0a0a0f)](https://www.nuget.org/packages/FlanderDev.RouteGen.Generators)

</td>
</tr>
</table>

## 📦 Other projects
| Project | What it does | Stack |
|---|---|---|
| [Windows-Service-Installer](https://github.com/FlanderDev/Windows-Service-Installer) | Interactive console-app for managing  Windows services | ![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white) |
| [ImageSorter](https://github.com/FlanderDev/ImageSorter) | Android app for sorting images into folders | ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| [Pixel-Monitor-and-Trigger](https://github.com/FlanderDev/Pixel-Monitor-and-Trigger) | Watches a pixel or screen area and triggers actions when it changes | ![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white) |
| [MassImageRenamer](https://github.com/FlanderDev/MassImageRenamer) | An extremely simple image sorter that works | ![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white) |
| [MikuFlasher](https://github.com/FlanderDev/MikuFlasher) | A joke app that fakes a camera-based verification process | ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |
| [spirited_code](https://github.com/FlanderDev/spirited_code) | Advent of Code across years and languages: [XOYZ69/spirited_code](https://github.com/XOYZ69/spirited_code) | ![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white) |

### ✂️ Useful gists
- [**Editable `Console.ReadLine`**](https://gist.github.com/FlanderDev/668c7ec28cd1d7c28d4cde939462f890): prefill the console input buffer and let the user edit it, with arrow keys, backspace and delete.
- [**`CliFillAttribute`**](https://gist.github.com/FlanderDev/446704382ace664e719fa82f0e530a90): create and populate a class instance from console input, driven by attributes.

## 👋 About me
<img align="right" width="260" alt="Profile picture: gremlin self-personification wearing a Bocchi the Rock shirt" src="https://github.com/user-attachments/assets/e045f578-35b8-4694-8f95-e9e79ccc9e85" />

- 🔌 Started out as a vocational **electrician**, got hooked on programming, and now work as a **software developer/engineer** with experience in several international environments.
- 💜 **C#** won my heart, but I keep widening my tools; **Kotlin/Java** for Android, a bit of **Rust**.
- 🕹️ I love learning how software works. Modding Unity games via BepInEx keeps that interest up .Although IL2CPP can be a hassle.
- 🌐 Being terminally online definitely helps 😄
- ⚡ **Fun fact:** I love playing sports, and yet I'm lazy as hell.
- 💬 Talk to me about anything .NET, source generators, modding, anime, or IT in general & you've got my intrest.

<br clear="right"/>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FlanderDev/FlanderDev/output/snake-dark.svg" />
  <img alt="Contribution snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/FlanderDev/FlanderDev/output/snake-light.svg" width="100%" />
</picture>
