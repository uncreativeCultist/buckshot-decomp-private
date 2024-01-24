# Buckshot Roulette Decompilation

![](https://dcbadge.vercel.app/api/shield/435509065339240449)

A full decompilation of the game Buckshot Roulette by Mike Klubnika.
I own no assets contained in this repo.

**I ASK YOU DO NOT SHARE THIS REPO WITH ANYONE.**

**IF MIKE KLUBNIKA ASKS, THIS REPO WILL BE TAKEN DOWN UPON REQUEST.**
## Notes
- Files are highly compressed in .7z format due to file size restrictions.
- The source code's ```main.tcsn``` files are compressed due to file size restrictions.
- I might've screwed up the source code on the Github repo. Releases will be unaffected, however I just thought it was important to let you all know.

## Installation
This section will cover the basics of installing the Godot Engine, and adding to project to it.
### Downloading the Godot Engine

1. Go to [the steam page for the Godot Engine](https://store.steampowered.com/app/404790/Godot_Engine/) and add it to your library.

2. Right click on Godot Engine in your library and go to betas and select ```STABLE-4.1 - 4.1.X STABLE BRANCH```, then install the engine as normal.
Note: Newer versions **will work**, however they do have issues. All materials will need recompilation and will scream errors in the console, cause lagspikes, and will have bugged textures.

### Adding the project to the Godot Engine

1. Download your desired version from the [releases](https://github.com/imcommonsense/buckshot-decomp-private/releases) section of this repo, and extract the zip into a folder.

2. Open the Godot Engine and click on the import button on the sidebar, and select the project.godot file in your extracted folder, then click ```Import & Edit```.

3. Wait for it to load, then navigate into res://scenes and select your scene.
## Compiling/Exporting the Game
This section will cover the basics of exporting the game.
#
1. Click the tab at the top right of the Godot Engine labeled ```Project``` and select ```Export```.

2. Click the ```Add``` and select what platform you are exporting the game for.
NOTE: Without major modifications, Buckshot Roulette will **NOT** function on some devices due to the Vulkan requirement.

3. Follow any instructions the Godot Engine gives you at the bottom of the window.
3.1 If you're exporting for Windows, it will say ```The rcedit tool must be configured in the Editor Settings (Export > Windows > rcedit) to change the icon or app information data.``` If you care about the icon for the game, you can set it up with the instructions [here,](https://docs.godotengine.org/en/stable/tutorials/export/changing_application_icon_for_windows.html) otherwise, you can ignore it and instead scroll down to ```Application``` and enable ```Modify Resources```.

4. Make sure to enable ```Embed PCK``` and click ```Export Project....``` 
‎

If everything goes well, you'll have two EXE files, one being a debug console wrapper. 
Running this wrapper will launch the game, except with a console for debug purposes. If you wish, you can get rid of the console wrapper.