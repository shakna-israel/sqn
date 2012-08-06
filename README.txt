README:

This a batch-file based mod for Skyrim.

It's based on the idea that you should be able to create a decent game-mod using only the shell provided with the game, as it is fairly extensive. So no, the mod isn't something that creates a lot of non-vanilla items, quests or locations, but it should spice it up somewhat if your looking for something different.

To install the mod:

Go to "C:\Users\YOUR_USER_NAME\Documents\My Games\Skyrim" in Explorer, replacing YOUR_USER_NAME with the name of your current user.
Open the file called Skyrim.ini in a text editor and under the [General] tag past this line:

SStartingCell=StendarrsBeaconExterior01

For example, the section of my Skyrim.ini file looks like this:

[General]
sLanguage=ENGLISH

uExterior Cell Buffer=36

SStartingCell=StendarrsBeaconExterior01

Once this is done, place all other files in your Skyrim Data folder. (The Data folder is located at:

C:\Program Files (x86)\Steam\steamapps\common\skyrim\Data

If you're on 32-bit:

C:\Program Files\Steam\steamapps\common\skyrim\Data

or

SOMEWHERE ELSE if you have a non-steam version, and if that's the case, chances are you know where to look.

After this open Skyrim, start a new game, then hit the ~ key, and type the following (qithout quotes):

"bat start"

Then hit the enter key, and then the ~ key again.