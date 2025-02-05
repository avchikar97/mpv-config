# mpv-config
My MPV config. The input.conf is based on an old guide which in turn linked to an input.conf which uses VLC keyboard shortcuts. I will link it here if I ever find it again.

Some scripts may be outdated. See [Lua Script Sources](#lua-script-sources) for the latest and greatest.

To use this repo, copy all contents except the README.md to your mpv folder to end up with the following file structure:
```
.
│   mpv.exe
│   discord-rpc.dll
│   settings.xml
└───mpv/
    │   fonts.conf
    │   input.conf
    │   mpv.conf
    │
    ├───fonts/
    │       ...
    │
    ├───script-opts
    │       ...
    │
    ├───scripts
    │       ...
    │
    └───shaders
            ...
```

# Lua Script Sources

[autoload](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua)

[manga-reader](https://github.com/Dudemanguy/mpv-manga-reader/blob/master/manga-reader.lua) (added webm to ext at top)

[mpv-discordRPC](https://github.com/noaione/mpv-discordRPC)

[pause-when-minimize](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/pause-when-minimize.lua)

[trackselect](https://github.com/po5/trackselect)

[mpv-webm](https://github.com/ekisu/mpv-webm)

# Credits

[input.conf](/mpv/input.conf) was originally based on https://gist.github.com/abhimanyu003/f63c38c6fa09bd65e875 with some tweaks over the years