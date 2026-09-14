# Slay-monarch---Genderless-Hairstyle-for-Chef-RPG

# Description
As the name implies, this mod removes the association between gender and hairstyles.
The mod patches the methods responsible for hairstyles selection, in a way that both genders have access to all the hairstyles in-game. After that I just adjusted the methods around this change so the game can recognize the new styles. 

## Performance 
It shouldn't affect performance in a big way, but I did encounter some lag in the earlier versions of it - caused by, mainly, the random npc generation - but I believe I fixed the cause of it. If you feel any drop in frame rate don't hesitate to post here and I'll look into it. 
## *AI Usage Disclaimer*
This is my second mod ever - you may know me from the Dialogue Expansion Mod - so I still consulted LLMs for debugging and to clarify some doubts I had about Harmony and C#. But overall, I tried to make the mod myself any time I could.  
# Install
This mod needs the following dependencies to work:
- BepInEx (5.4.23.5), which can be found [here](https://github.com/BepInEx/BepInEx).
  - Download the 5.4.23.5 release for your OS and follow installation instructions.
    - If you're running the game on Linux with a compatibility layer (Ex.: Proton), you should follow the windows instruction and add
```
WINEDLLOVERRIDES="winhttp=n,b" %command%
```
to the game launch option.

After BepInEx is properly installed and launched (you should have the path "~/Chef RPG/BepInEx/plugins/" if everything went well), just extract the zip file content to the folder "plugins" and start the game.
# Uninstall
This mod shouldn't cause any problem to uninstall. Just delete the mod folder and you're good to go.
