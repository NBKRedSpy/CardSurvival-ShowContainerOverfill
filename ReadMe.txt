[size=4][b]Show Container Overfill[/b][/size]

[size=3][b]Bar Indicator[/b][/size]

Changes the weight bar to red if a container is holding more than the weight bonus.  For example, Sacks and Travois both can carry more than the weight they can offset.

[size=3][b]Overflow Limit Option[/b][/size]

Adds a toggle to limit filling containers to only their weight bonus.

This allows the user to fill a container without needing to manually add and remove items until exactly at or below the weight bonus.

This can be toggled on or off in real-time using the hotkey (L by default).

When the overfill lock is enabled, the bars will be changed to a slightly darker yellow.


[size=4][b]Options[/b][/size]

[font=Courier New] 
| Name                     | Default                 | Description             |
| ------------------------ | ----------------------- | ----------------------- |
| Default Bar Color        | Yellow - Game's default | The default color of    |
|                          | color                   | the bar when not        |
|                          |                         | overfilled or locked.   |
|                          |                         |                         |
| Overfill Lock Color      | Darker Yellow           | The color of the        |
|                          |                         | storage bars when       |
|                          |                         | overfill lock is        |
|                          |                         | enabled and under the   |
|                          |                         | weight bonus.           |
|                          |                         |                         |
| Overfill Color           | Red                     | The color of the        |
|                          |                         | storage bars when a     |
|                          |                         | container contains more |
|                          |                         | weight than the weight  |
|                          |                         | bonus.                  |
|                          |                         |                         |
| Overfill Toggle Key      | L                       | Toggles limiting        |
|                          |                         | containers to only      |
|                          |                         | accept cards up to the  |
|                          |                         | weight bonus.  For      |
|                          |                         | example, A sack can     |
|                          |                         | contain 1000 weight,    |
|                          |                         | but only 600 weight is  |
|                          |                         | 'free'                  |
|                          |                         |                         |
| Start Overfill Toggle    | false                   | If true, the game will  |
| Enabled                  |                         | start with the overfill |
|                          |                         | limit enabled.          |
[/font]


[size=3][b]Configuration Note[/b][/size]

The easiest way to edit the above options is to use the BepInEx Configuration Manager found here:  https://github.com/BepInEx/BepInEx.ConfigurationManager
It supports a UI which can select colors as well as easily bind keys.

Alternatively, the configuration file is located in the game's directory at [code]BepInEx\config\ShowContainerOverfill.cfg[/code]


[size=4][b]Installation [/b][/size]

This section describes how to manually install the mod.

**If using the Vortex mod manager from NexusMods, these steps are not needed.**

[size=3][b]Overview[/b][/size]

This mod requires the BepInEx mod loader.

[size=3][b]BepInEx Setup[/b][/size]

If BepInEx has already been installed, skip this section.

Download BepInEx from https://github.com/BepInEx/BepInEx/releases/download/v5.4.21/BepInEx_x64_5.4.21.0.zip

* Extract the contents of the BepInEx zip file into the game's directory:
[code]<Steam Directory>\steamapps\common\Card Survival Tropical Island[/code]

    __Important__:  The .zip file *must* be extracted to the root folder of the game.  If BepInEx was extracted correctly, the following directory will exist: [code]<Steam Directory>\steamapps\common\Card Survival Tropical Island\BepInEx[/code].  This is a common install issue.

* Run the game.  Once the main menu is shown, exit the game.
    
* In the BepInEx folder, there will now be a "plugins" directory.

[size=3][b]Mod Setup[/b][/size]

* Download the ShowContainerOverfill.zip.  
    * If on Nexumods.com, download from the Files tab.
    * Otherwise, download from https://github.com/NBKRedSpy/CardSurvival-ShowContainerOverfill/releases/

* Extract the contents of the zip file into the [code]BepInEx/plugins[/code] folder.

* Run the Game.  The mod will now be enabled.

[size=4][b]Uninstalling[/b][/size]

[size=3][b]Uninstall[/b][/size]

This resets the game to an unmodded state.

Delete the BepInEx folder from the game's directory
[code]<Steam Directory>\steamapps\common\Card Survival Tropical Island\BepInEx[/code]

[size=3][b]Uninstalling This Mod Only[/b][/size]

This method removes this mod, but keeps the BepInEx mod loader and any other mods.

Delete the [code]ShowContainerOverfill.dll[/code] from the [code]<Steam Directory>\steamapps\common\Card Survival Tropical Island\BepInEx\plugins[/code] directory.

[size=4][b]Compatibility[/b][/size]

Safe to add and remove from existing saves.

[size=4][b]Change Log [/b][/size]

[size=3][b]2.1.0[/b][/size]
* Fixed drag and drop not handling overfill lock.

[size=3][b]2.0.0[/b][/size]

* Added "prevent overfill" toggle functionality

[size=3][b]1.0.0  [/b][/size]

* Initial Release




