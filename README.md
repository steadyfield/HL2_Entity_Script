# HL2_Entity_Script
Entity Script for HL2 Games, Aiming to bring a GMOD-like Experience in Original HL2

# How to use
(1) Create a new folder named as `ent` in [MOD_NAME]/cfg, for example hl2/cfg, episodic/cfg, ep2/cfg.
(2) Put all the files into the `ent` folder.
(3) Run the game, enter a map, aim at ground, in console enter `exec ent/[SCRIPT_FILENAME]`, the `.cfg` suffix is not required. 
Note #1: for some scripts, you may need to `noclip` to the mid air and aim directly down to the ground, then `exec` the script. Otherwise, the relative positions between the entities in the script may not be correct.
Note #2: for most of the scripts, one script can be run ONLY ONCE in a map or saved game. Do NOT RUN A SINGLE SCRIPT FOR MULTIPLE TIMES IN A MAP OR SAVED GAMES. Otherwise the newly spawned entities by the script may not be working. This is because the entity name of them are the same. And custom enetity scripts do not have dynamic-naming feature. You have to make a copy of the `.cfg` file and change their entity names, if you want to have more group of the entities in the script.