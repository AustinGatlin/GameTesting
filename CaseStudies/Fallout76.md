# Fallout 76 bugs 

### Bug 1
The bug: Radroaches opening doors. 

Box type: This bug should have been found in whitebox testing. Since the whitebox teseters know exactly how things should react and are familiar with the inner workings of the game, they should have been able to see that an AI is behaving in a way that they never intended. 

Type of testing: This would fall under unit testing. Radroaches opening doors seems to be an issue directly related to Radroaches alone. As such, a unit test on radroaches should be able to locate the exact issue. 

How I would identify the bug: I would start the game. Load into a lobby, and find a radroach. Having found the radroach, I would then attack it so that it would follow me. While it's following me, I would lead it to a location that has a closable door. I would then get on the opposite side of the door from the radroach and then close it.

### Bug 2
The bug: Carrying too many holotapes causes the holotapes towards the buttom of the list to not load into terminals.

Box type: This bug should have been caught during blackbox testing. The reason that this would be blackbox testing is because it is a bug that would likely only appear during regular gameplay by someone not familiar with the game, and not during unit or smoke test. A whitebox tester would be more likely to simply check to see if the holotapes worked one at a time whereas in a blackbox environment the user would be more likely to jump from one activity to another, and as a result, run into a bug that required a rather large backlog of unused holotapes. 

Type of testing: The type of testing that should be used to identify and this bug is integration testing. Since the bug is one that involves several different gameplay systems such as the inventory, quest and holotape system, it's likely that the bug is a result of an integration issue between two or more of those three systems. 

How I would identify the bug: To identify this particular bug, I would start a session on a new account with a new character. After creating a new character, I would then collect as many quests as I could. Once reaching 25 quests collected, but not completed, I would then proceed to a terminal to use the holotapes. Once there, I would begin by trying to load the bottom holotape. If it works, then repeat the process 3 more times to ensure that it does consistently work. If it doesn't, make a bug report ticket and repeat the steps after each potential fix for the bug has been made. 

### Bug 3
The bug: Monsters instantly knowing where the player is after a stealth attack. 

Box type: This bug should have been identified in whitebox testing. A whitebox tester is exactly the type of tester that would be testing core game functionality such as sneaking.

Type of testing: This bug would be found and identified during functionality testing. If a monster isn't responding to being sneak attacked, then the portion of the monster's functionality that handles detection is not working properly and should have been caught during a functoinality test on the AI.

How I would identify the bug: I would start a new game, join a session and use the developer's console commands and tools to automatically increase my character's sneak to maximum. Then I would find various monsters and sneak attack them and wait to see if they instantly know my location or not. 

### Bug 4 
The bug: 

Box type: 

Type of testing:

How I would identify the bug:


### Bug 5

The bug: 

Box type: 

Type of testing:

How I would identify the bug:
