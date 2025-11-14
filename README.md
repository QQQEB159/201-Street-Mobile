This is the 201 Street source enjoy

theres some issues on low end computers but lowk we tried our best this was supposed to come out on halloween originally
and theres not gonna be a patch atm so sorry !

Runs on Nightmare Vision (dev branch)

Original Nightmare Vision Source: https://github.com/DuskieWhy/NightmareVision

## How to compile NMV Engine

### Quick Note
- Haxe 4.3.6 or newer is expected
- This engine ENFORCES the use of local libraries with hxpkg/hmm to prevent issues in relation to `hxvlc`
- The expected library versions are listed within the .hxpkg file. 

if compilation errors arise, Ensure your Haxe version is correct and your haxelibs match what is listed in the .hxpkg file

### Download the prerequisites... (skip this if you already have compiled any fnf project, or any flixel project basically lol)

[Haxe](https://haxe.org/download/)

[Git](https://git-scm.com/downloads)

[VS Community](https://visualstudio.microsoft.com/vs/community/)

within the VS Community Installer, download `Desktop development with c++`

### Download the projects required libraries...

In a cmd within the project directory, in order run...

> haxelib install hxpkg

> haxelib run hxpkg setup

> haxelib run hxpkg install

After that is complete, run `lime test windows` and you should be compiling
