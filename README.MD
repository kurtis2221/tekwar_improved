## Info
It contains 3 versions:
- tekwar_imp - main improvement mod, map files are not included
- tekwar_coop - experimental singleplayer level coop mod, can easily desync
- tekwar_min - mostly untouched with freelook, faster ladder climbing and fixed switch sprite
- TILES016.ART - only used by the coop mod

There might be some unnecesary OBJ files included.

## Compile
Watcom C 10 is required.

I used Watcom C 10.5 to compile the exe.

1. In DOS cd into one of the folders, then cd into it's src folder
2. Run: wmake /f tekwar.mak
3. After it finishes without errors, the run folder should contain the exe