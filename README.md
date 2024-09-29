# LMSH2-intro

This mod for **LEGO Marvel Superheroes 2** allows you to skip the game intro.

<img src="screenshot.webp" title="Screenshot from game - Intro" width="40%">

## About

> ⚠️ **Tested on macOS only!** The file structure appears similar to Windows, but I haven’t tested it. If it works on Windows, please update the README or create an issue. Thank you!

## Installation

### Game files unpacked:

If you already unpack game and have access to game files. (You can see folders and files in the game directory)

1. Download archive from release page
2. Follow the folder structure in the downloaded archive and replace the corresponding files in your game folder

### Game files packed:

If you don’t have unpacked files (If you only see __disc_ and .dat files in the game folder)

> ⚠️ **It's good idea to backup original game files!**

1. Download game (I use Steam version, don’t know if it works on other versions)
2. If you have DLC, download them too
3. Download [QuickBMS](http://aluigi.altervista.org/papers/quickbms.zip)
5. Download [ttgames.bms](http://aluigi.altervista.org/bms/ttgames.bms) script for QuickBMS
6. Extract QuickBMS in folder, run `quickbms.exe` as Administrator
7. Select `ttgames.bms` file
8. Select all `.dat` files in game folder (including `dlc .dat` files)
9. Select folder where place unpacked files (new folder on Desktop is good)
10. After unpack complete - remove `__disc__` and all `.dat` files from original game folder
11. Move unpacked files to original game folder
12. Download archive from release page
13. Follow the folder structure in the downloaded archive and replace the corresponding files in your game folder

>💡 Note: Unpacking can be a long process and the unpacked game will be significantly larger (e.g., my game went from 25GB to 32GB after unpacking).

P.S. For Windows process is same (I unpacked files on Windows), but according to [this page](https://www.pcgamingwiki.com/wiki/Engine:Nu2#Patching_executables_to_run_extracted) , you may need to patch the game’s .exe file. On macOS, no patching is needed, simply unpack and place unpacked files.

If you have any trouble, follow this video: [https://www.youtube.com/watch?v=_EQ3hPrh0V8](https://www.youtube.com/watch?v=_EQ3hPrh0V8)


## Uninstall

Replace files in game folder with files from `/source/backup/`


## Paths

This is macOS paths to the game folder and mod files.

Game folder:
```bash
~/Library/Application Support/Steam/steamapps/common/LEGO Marvel Super Heroes 2
```

Game files folder:
```bash
~/Library/Application Support/Steam/steamapps/common/LEGO Marvel Super Heroes 2/LEGOMarvelSuperHeroes2Data/
```

This paths will be available after game files unpacking:

Loading screen config:
```bash
~/Library/Application Support/Steam/steamapps/common/LEGO Marvel Super Heroes 2/LEGOMarvelSuperHeroes2Data/CUT/LOADINGSCREEN/LOADINGSCREEN.TXT
```