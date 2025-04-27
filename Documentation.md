# FakeManHunt
Fake ManHunt (Documentation) 

## Commands
###
- Assigning players to groups. There are two groups "Speedrunner" and "Hunter".
- The command to assign a speedrunner is ``` /manhunt set "player name" speedrunner ```
- And to assign a player to the Hunter group, the command is ``` /manhunt set "player name" hunter ```
The command to start the ManHunt is ``` /manhunt start ``` (the ManHunt will start if there are at least 2 hunters in the team)
Command to stop the game - ``` /manhunt stop ```
When a player from the Speedrunner group dies, items and experience are retained by the player. This function can be disabled with the command - ```/manhunt save false```
And turn it back on with the command - ```/manhunt save true```
The "Speedrunner" team /back group can return to the place of their death.
The "Speedrunner" group should have the color "Green" in the chat and tab.
The "Hunter" group should have the color "Red" in the chat and tab.
