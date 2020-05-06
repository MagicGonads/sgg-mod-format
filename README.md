# SuperGiantGames Mod Format
Format for making and loading lua mods for SuperGiantGames' games (Bastion, Transistor, Pyre, Hades)

Check the [Wiki](https://github.com/MagicGonads/ssg-mod-format/wiki) for the important information!

To use `modimporter.py` put it in the game's Content folder.
For full functionality it also requires the [python SJSON module](https://pypi.org/project/SJSON/).

When run with python it will read the mods in the folders in `Content/Mods` and implement the changes to the base files.
Check `Content/Backups` for the base files prior to importing.
