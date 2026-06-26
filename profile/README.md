<div align="center">

#  The UnionCrax Team

*We prefer dangerous freedom over peaceful slavery.*

[![Website](https://img.shields.io/badge/Website-union--crax.xyz-0078d4?style=for-the-badge&logo=firefox-browser&logoColor=white)](https://union-crax.xyz)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://union-crax.xyz/discord)
[![GitHub Org Stars](https://img.shields.io/badge/dynamic/json?label=Total%20Stars&query=%24.stargazers_count&url=https%3A%2F%2Fapi.github.com%2Forgs%2FUnionCrax-Team&color=ffd700&style=for-the-badge&logo=github)](https://github.com/UnionCrax-Team)

</div>

---

## 👋 About Us

We're **UnionCrax Team**, a small group of developers building open-source game tools, launchers, and utilities. Our focus is on:

-  **Steam API tooling** - bypass and compatibility layers for game preservation
-  **Game launchers** - fast, modern apps for managing and launching games
-  **Controller APIs** - input handling for games without native Steam Input
-  **Workshop tools** - mod and addon management made simple

---

##  Our Projects

###  Flagship Tools

<table>
<tr>
<td width="33%">

#### [uc-online2](https://github.com/UnionCrax-Team/uc-online2)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/uc-online2?style=flat-square&color=ffd700)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/uc-online2?style=flat-square)
![Issues](https://img.shields.io/github/issues/UnionCrax-Team/uc-online2?style=flat-square)

Custom Steam API `.dll` drop-in replacement that spoofs your game as Spacewar (or any free-to-play game or any games you own already) by default. Features plugin loader, SteamStub bypass, Remote Storage fallback, and broad Steamworks.NET / Facepunch compatibility.

`C++` · `Steam API` · `DLL` · `Spacewar`

</td>
<td width="33%">

#### [uc-online](https://github.com/UnionCrax-Team/uc-online)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/uc-online?style=flat-square&color=ffd700)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/uc-online?style=flat-square)
![Issues](https://img.shields.io/github/issues/UnionCrax-Team/uc-online?style=flat-square)

The original Steam spoofer, makes Steam think you're playing Spacewar (App ID 480), enabling online multiplayer via the Spacewar lobby system. Uses a separate launcher executable to work. The foundation that started it all.

`C++` · `Steam` · `Bypass` · `Multiplayer`

</td>
<td width="50%">

#### [uc-online1.1](https://github.com/UnionCrax-Team/uc-online1.1)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/uc-online1.1?style=flat-square&color=ffd700)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/uc-online1.1?style=flat-square)
![Issues](https://img.shields.io/github/issues/UnionCrax-Team/uc-online1.1?style=flat-square)

A full rewrite and refactor of the old C# code for the very first version of uc-online but instead of loading the game's steam_api dlls, it goes straight for the steamclient dlls in your Steam installation path to truly achieve a universal fix like I originally intended it to be. It works as a separate launcher to the game once again, but this time it's easier to figure it out.

`C#` · `SteamClient DLL` · `Launcher` · `Multiplayer`

</td>
</tr>
</table>

###  Launchers & Apps

<table>
<tr>
<td width="33%">

#### [UnionCrax.Direct](https://github.com/UnionCrax-Team/UnionCrax.Direct)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/UnionCrax.Direct?style=flat-square&color=ffd700)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/UnionCrax.Direct?style=flat-square)
![Release](https://img.shields.io/github/v/release/UnionCrax-Team/UnionCrax.Direct?style=flat-square&include_prereleases)

A fast Electron desktop app for browsing, downloading, and launching games from the UC library. Features pause/resume downloads, auto-updates, game library management, and sync with the UC website.

`TypeScript` · `Electron` · `React` · `Vite`

</td>
<td width="33%">

#### [UnionCrax.Launcher](https://github.com/UnionCrax-Team/UnionCrax.Launcher)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/UnionCrax.Launcher?style=flat-square&color=ffd700)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/UnionCrax.Launcher?style=flat-square)

Native launcher companion for UnionCrax.Direct. Handles game process launching and management on the C++ side for performance-critical operations.

`C++` · `Launcher` · `UC.Direct`

</td>
<td width="33%">
  
#### [uc.comms](https://github.com/UnionCrax-Team/uc.comms/)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/uc.comms?style=flat-square&color=ffd700)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/uc.comms?style=flat-square)

Docker deployable private chat you can self host and modify to your hearts content. Uses Lanyard API to connect to your discord account to give you your avatar and show your status. Web browser and PWA based, has an Android port and can be ported to iOS too, desktop app and the server that communicates with the webpage and connects all of clients. Very low data usage so it works great for limited networks and metered connections.

`node.js` · `Rust` · `HTML + .js` · `Capacitor / Cordova`

</td>
</tr>
</table>

###  Utilities & Extras

<table>
<tr>
<td width="33%">

#### [WorkItOut](https://github.com/UnionCrax-Team/WorkItOut)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/WorkItOut?style=flat-square)

Workshop mod & addon manager for games you "got". Browse, download, and install mods straight to any game's mod folder. 

`TypeScript` · `Electron` · `Mods`

</td>
<td width="33%">

#### [GCPad_API](https://github.com/UnionCrax-Team/GCPad_API)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/GCPad_API?style=flat-square)

Controller input API modeled after Steam Input - captures controller inputs through XInput / DInput / SDL2 / HID and translates them and remaps to custom outputs as well. Designed as a backend for frontends or games that don't use Steam from either using a Steam emu or not having Steam Input integrated.

`C++` · `XInput` · `DInput` · `SDL2`

</td>
<td width="33%">

#### [shadps4_cli-launcher](https://github.com/UnionCrax-Team/shadps4_cli-launcher)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/shadps4_cli-launcher?style=flat-square)

Minimal launcher for ShadPS4-CLI written in C and compiled with TCC. Lightweight wrapper for running ROMs through the emulator without needing to use cmd with the arguments.

`C` · `ShadPS4` · `CLI` · `TCC`

</td>
</tr>
</table>

<table>
<tr>
<td width="50%">

#### [hla-novr-desteamed_UC](https://github.com/UnionCrax-Team/hla-novr-desteamed_UC)
![Language](https://img.shields.io/github/languages/top/UnionCrax-Team/hla-novr-desteamed_UC?style=flat-square)

HLA NoVR Mod Launcher without Steam AppID launch requirements — runs `hlvr.exe` directly with the necessary arguments, bypassing Steam's game launch gating for Half-Life: Alyx.

`GDScript` · `HLA` · `NoVR` · `Godot`

</td>
<td width="50%">

#### [.github](https://github.com/UnionCrax-Team/.github)
You're looking at it! Organization profile, community health files, and shared workflows for the UnionCrax-Team organization.

`GitHub` · `Profile` · `Community`

</td>
</tr>
</table>

---

##  Stats

<div align="center">

![Repos](https://img.shields.io/badge/Public%20Repos-8-0078d4?style=for-the-badge&logo=github)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/unioncrax.direct?style=for-the-badge&label=UC.D%20⭐&color=ffd700)
![Stars](https://img.shields.io/github/stars/UnionCrax-Team/uc-online2?style=for-the-badge&label=uc-online2%20⭐&color=ffd700)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=UnionCrax-Team&layout=compact&theme=dark&hide_border=true&title_color=0078d4&text_color=c9d1d9&bg_color=0d1117&langs_count=8)](https://github.com/UnionCrax-Team)

</div>

---

##  Tech We Use

<div align="center">

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Steam](https://img.shields.io/badge/Steam-1b2838?style=for-the-badge&logo=steam&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)

</div>

---

##  Get Involved

We welcome contributions, bug reports, and feature suggestions on any of our public repos.

-  **Found a bug?** Open an issue in the relevant repository.
-  **Have an idea?** Reach out on Discord, we love community input.
-  **Want to fork?** Go for it. Check each repo's license for details.
-  **Request a game?** Head to [union-crax.xyz](https://union-crax.xyz) and let us know.

<div align="center">

[![Website](https://img.shields.io/badge/🌐%20Visit%20union--crax.xyz-0078d4?style=for-the-badge)](https://union-crax.xyz)
[![Discord](https://img.shields.io/badge/💬%20Join%20our%20Discord-5865F2?style=for-the-badge)](https://union-crax.xyz/discord)

*Made with ❤️ by the UnionCrax Team*

</div>
