Download both the BackupLivingSkyrimTextures.py script and texturelist.txt and put them in the same folder as the Living Skyrim folder.
Python required to run the script: https://www.python.org/downloads/

This script is for backing up textures for the purpose of downsizing them with [Cathedral Assets Optimizer](https://www.nexusmods.com/skyrimspecialedition/mods/23316) to get better performance/less stutters in Living Skyrim. You can choose between backing up all or landscape and/or architecture textures. If the performance profile in MO2 doesn't work well enough, then downsizing these textures might help as it reduces RAM & VRAM usage. I only included 4K and larger textures in the list, but excluded some, like interface, map, and sky/cloud textures.

How to downsize:
In Cathedral Assets Optimizer: select the folder this script backed up > Tick all boxes under the textures tab > 2x2 ratio > Run (it takes a pretty long time to complete)

Archive/zip the downsized textures to back them up.

After downsizing just replace the original files with them, don't do it through Mod Organizer. If you want to revert to original textures, just replace them with the files backed up by this script.

Made for Living Skyrim version 4.2.0.1
