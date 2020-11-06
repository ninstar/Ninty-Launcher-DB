# NL - TitleDB

Title database for https://github.com/ninstar/Ninty-Launcher.

Pull requests are welcome, but before doing so, read the section below.

## How to

All entries are stored in [database.ini](https://github.com/ninstar/NL-TitleDB/blob/main/database.ini), every entry needs an icon associated with its index in its filename (icons are stored in [/icons](https://github.com/ninstar/NL-TitleDB/tree/main/icons)).

An entry example:
```ini
[EntryIndex] ; {EntryType}
title="The Game DX"
tagA="The_Game_DX.exe"
tagB="\The Game DX"
tagC="\The Game DX\Game.exe"
```

**Requirements**
- Icons need to be in **.png** format and 1:1 proportion (the minimum size is ``256x256``).
- Titles can only be 32 characters longs.
- Tags can **never** be the same, regardless of their entry index.
- You can have up to 6 tags fo each entry (*A, B, C, D, E, F*).
- If the name of the executable is too ambiguous or generic, use the ``\``, Ninty will take into account the name of the folder to avoid tag conflicts.
- Optionally you can put a ``forward=1`` or ``shortcut=1`` to make Ninty set the application type automatically.
- The ``{EntryType}`` field must be **one** of those listed bellow, choose the one that best fits your entry.
	- ``{G}`` **Games** - The title says by itself.
	- ``{M}`` **Mods** - Mods and loaders official and unofficial games.
	- ``{A}`` **Applications** - Focused on general users: Applications for general purpose, multimedia, ect...
	- ``{T}`` **Tools** - Focused on advanced users: Editors and tools for software development, design, game modding creation, etc...
	- ``{E}`` **Emulators** - Exclusively for video game emulators.

## Credits

All the resources provided here were made possible thanks to the contribution of the following people:

* AlphaFenix  
* Arklem  
* Braguetta  
* Biel98765  
* igorsales73  
* IncrivelXand  
* Mexiboi  
* Nin★ (NinStar)  
* Ostrich101
* Seph  
* SiuLunar  
* Thewolensheep  
