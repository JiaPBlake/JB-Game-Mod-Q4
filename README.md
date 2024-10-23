Hi!

Once all the files from the PokemonTest branch have been downloaded to your device:
- Open the q4sdk.sln file with Visual Studio
- Make sure the Build Configuration is set to Release and not Debug. (x86)
- Build the solution.
- This should create a Win32 folder.

Inside the Win32 folder, there should be a Release folder that contains all of the necessary game data.  **Including the Gamex86.dll file** needed to run the mod.

Once you have Quake 4 downloaded, create a new folder in the Quake 4 folder. This will be your mod folder.  Copy the necessarily files from the __q4base__ folder into your mod folder.
Within the mod folder, you will need:
- the **game000.pk4** file (for Windows)
(idk yet if I want to include the Config file)
- and then the pak001 folder from the git repository (should should have every extra folder of mine except gfx and savegames), 


*Important.  When using these files for your mod, you may use the defFilesUsed folder as your def folder. Just be sure to rename it to "def"      <- NOT QUITE !!   bc of the pk4 file


