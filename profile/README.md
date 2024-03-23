[![](https://discordapp.com/api/guilds/410828272679518241/widget.png?style=banner2)](https://discord.gg/Mvk7W7gjE4)
[![](https://raidcore.gg/Resources/Images/Patreon.png)](https://www.patreon.com/bePatron?u=46163080)

# About Raidcore
There's not much here just yet, but you can visit our website and join our discord!

# About contributing to open-source projects
## Project versioning
All projects are versioned (publically facing) as follows: `YYYY.MM.DD.{HH*60+mm}`
This versioning was chosen as it's immediately apparent by the date from when it is and the shortened Build number in the end fits in a i16/u16.
Most C++ projects include a pre-compile step generating a `Version.h` to include within the project.
If they do not use this versioning yet, please do not add your own versioning, but instead add this system.

## Build System and Packages/Modules
All projects use Visual Studio's Build System and git submodules for packages.
If you are contributing to a project and want to use another build system, keep those files only locally.
Use git submodules for packages.
