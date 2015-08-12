# gmod_luasec

Modules for Garry's Mod that add bindings for OS sockets through [luasec][1].

## Info

This project is composed by the Lua modules (in includes/modules) and the internal (binary) module (ssl.core).
You can also refer to this project as gm_luasec or LuaSec for Garry's Mod.
The Lua files go into lua/includes/modules (just copy includes from this repo onto lua) and the binary module goes into lua/bin.

Mac was not tested at all (sorry but I'm poor).

If stuff starts erroring or fails to work, be sure to check the correct line endings (\n and such) are present in the files for each OS.

This project requires [garrysmod_common][2], a framework to facilitate the creation of compilations files (Visual Studio, make, XCode, etc). Simply set the environment variable 'GARRYSMOD_COMMON' or the premake option 'gmcommon' to the path of your local copy of [garrysmod_common][2].


  [1]: https://github.com/brunoos/luasec
  [2]: https://bitbucket.org/danielga/garrysmod_common
