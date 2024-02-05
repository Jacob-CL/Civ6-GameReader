Civ6Analysis
Game Logs are stored here:

C:\Users\User\AppData\Local\Firaxis Games\Sid Meier's Civilization VI\Logs
The files stored in here are WIPED upon launch. When the game launches, all files are removed permanently and the following are created:

Renderer.txt: Basic launch related configurations
Engine.txt: Application Session Hash, Hostname Hash, and Bug collection information.
Startup.txt: .. start up logs
Database.txt: .. boring database initilization logs
Localization.txt: Language Configurations
FiraxisLive.txt: FireAxisLive connection logs(?)
ArtDef.txt: Logs on .blp files (texture files?)
UserInterface.txt: Logs on loading UI
ForgeUI_BLPTextureLoader.txt: Texture overwrite logs
UIWarnings.csv:
Modding: .. modding logs
GameCoreAppConfig: more to do with modding
Lua.txt: Waits for the game to start, and logs map creation
Profile.csv: constantly being written to with pings?
VisManager.txt: Empty at launch
EOS.txt: HTTP logs trying to reach out to Epic Games - failing
When a new game is started / loaded, the following files are created:

net_connection_debug.txt:
net_message_debug.txt:
LoadGameViewState.txt:
AI_Diplomacy.csv:
AI_Governors.csv:
AI_Knowledge.csv:
AI_Military.csv:
AI_Opertation_Eval.csv:
AI_Planning.csv:
AI_Religious.csv:
AI_Research.csv:
AI_Victories.csv:
AStar_GC: Tracks the movement of each unit across the map in this format:
Game Turn, Player, Unit, From X, From Y, To X, To Y, Info, Checksum
e.g 102, LOC_CIVILIZATION_MACEDON_NAME, UNIT_SCOUT (262144), 21, 3, 21, 2, 16400, afa44abc
Game_Emergencies.csv:
Game_GreatPeople.csv:
Game_HeroesManager_HeroStats.csv:
Game_HeroesManager_PlayerStats.csv:
Game_PlayerScores.csv:
Player_Stats.csv:
Player_Stats2.csv:
World_Congreess.csv:
AStarAPP.txt:
CultureBordersLog.txt:
VFXSystem.txt:
SynthesisLog.txt:
AI_Chokepoint.csv:
AI_GovtPolicies.csv:
AI_UnitEfficiency.csv:
DiplomacySummary.csv:
RandCalls.csv:
UnitOperations.txt:
GameCore.txt:
Draw hexagonal map.
Read, extract player co-ordinates
