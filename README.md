Hi!

Once all the files from the PokemonTest branch have been downloaded to your device:
- Open the q4sdk.sln file with Visual Studio
- Make sure the Build Configuration is set to Release and not Debug. (x86)
- Build the solution.
- This should create a Win32 folder.

Inside the Win32 folder, there should be a Release folder that contains all of the necessary game files.  **Including the Gamex86.dll file** needed to run the mod.

Once you have Quake 4 downloaded, create a new folder in the 'Quake 4 folder' (where ever Steam installed it for you). This new folder will be your mod folder.  Copy the necessary files from the __q4base__ folder into your mod folder.
Within your mod folder, you will need:
- the **game000.pk4** file (this one is for Windows) copied DIRECTLY from q4base
- All of the Folders within the defFilesUsed folder from the PokemonTest repository, as well as the Quake4Config file (for custome hotkeys and command shortcuts. Like pressing X to give all, and K to spawn a strogg enemy).

Now that your mod folder is setup, and you have built the q4sdk.sln solution in Visual Studio (With the above mentioned settings), you should have the **Gamex86.dll file** in you Win32 folder. Open the game000.pk4 file with 7-zip, and place the Gamex86.dll file into the game000.pk4 file using 7-zip. Close the 7-zip window, and your mod should be good to go!



