###Test cases for minigames###

##TEST CASES FOR "GALAXY DAME" MINIGAME##
| ID | Test case | Steps | Expected result | Actual result | Status |
|---|---|---|---|---|---|
| GDM-001 | Info: Pressing the "Info" Button displays the manual guide to game rules. | 1. Choose "Galaxy Dame" game from arcade 2. Select Info 3.) Press any button to display each game rule in text | Game rule text is displayed in order | Game rules text is properly displayed in order | Pass |
|---|---|---|---|---|---|
| GDM-002 | Score: Pressing the "Score" Button displays the current scoreboard from most points to least | 1. Choose "Galaxy Dame" game from arcade 2. Select Scores | Scoreboard lists character scores in order from greatest to least | Game successfully displays game scores in order | Pass |
|---|---|---|---|---|---|
| GDM-003 | Play: Pressing "Play" initiates minigame | 1. Choose "Galaxy Dame" game from arcade 2. Select Play | Minigame Initiates | Minigame successfully initiates | Pass |
|---|---|---|---|---|---|
| GDM-004 | Right click to attack | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3. Right-click the mouse to shoot a bullet | Bullet gets shot from bottom to top of screen on click | Bullet gets shot as expected| Pass |
|---|---|---|---|---|---|
| GDM-005 | Bullet object destruction | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3.) Shoot bullet | Bullet object destroys itself upon reaching the other end of the screen or upon impact with an enemy | Bullet successfully destroys itself | Pass |
|---|---|---|---|---|---|
| GDM-006 | Enemy death | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3.) Shoot a bullet and make contact with the enemy | Enemy object destroys itself upon bullet impact within the hit box | Enemy successfully destroys itself | Pass |
|---|---|---|---|---|---|
| GDM-007 | Player score increases upon enemy death | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3.) Shoot a bullet and make contact with the enemy. 4.) Observe points at the top right corner | Points increase by 100 for each destroyed enemy | Points increase as expected | Pass |
|---|---|---|---|---|---|
| GDM-008 | Enemy speed increases with level up | 1. Choose "Galaxy Dame" game from arcade 2. Select Play. 3.) Kill 10 enemies | Game mode "levels up" and leads to an increase in enemy frequency | Enemy deployment increases successfully | Pass |
|---|---|---|---|---|---|
| GDM-009 | Enemy speed increase caps at level 7 | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3.) Level up past level 7  | Enemy frequency does not continue to increase | Enemy frequency successfully capped | Pass |

##TEST CASES FOR "Maze Game" MINIGAME##
| ID | Test case | Steps | Expected result | Actual result | Status |
|---|---|---|---|---|---|
| GDM-001 | Info: Pressing the "Info" Button displays the manual guide to game rules. | 1. Choose "Maze Game" game from arcade 2. Select Info 3.) Press any button to display each game rule in text | Game rule text is displayed in order | Game rules text is properly displayed in order | Pass |
|---|---|---|---|---|---|
| GDM-002 | Score: Pressing the "Score" Button displays the current scoreboard from most points to least | 1. Choose "Maze Game" game from arcade 2. Select Scores | Scoreboard lists character scores in order from greatest to least | Game successfully displays game scores in order | Pass |
|---|---|---|---|---|---|
| GDM-003 | Play: Pressing "Play" initiates minigame | 1. Choose "Maze Game" game from arcade 2. Select Play | Minigame Initiates | Minigame successfully initiates | Pass |
|---|---|---|---|---|---|
| GDM-004 | Arrow keys to move | 1. Choose "Maze Game" game from arcade 2. Select Play 3. Use arrow keys to move | Arrow keys will Move player across the map by one block each | Arrow Keys move as expected | Pass |
|---|---|---|---|---|---|
| GDM-005 | Game round resets on end of timer | 1. Choose "Maze Game" game from arcade 2. Select Play 3.) wait for first timer to end | Score goes up for Angel, and stays at zero for the player, and the round resets the player to the front of the maze | Round resets successfully | Pass |
|---|---|---|---|---|---|
| GDM-006 | Game lasts ten rounds | 1. Choose "Maze Game" from Arcade 2. Select Play 3.) Wait for ten rounds to end | Game lasts ten rounds before moving to "game over" game state | Game over reached successfully | Pass |
|---|---|---|---|---|---|
| GDM-007 | Angel Object Spawn | 1. Choose "Maze Game" from Arcade 2. Select Play 3.) Move upwards immediately, then down five, right four, down two, then uptw, right seve, and up five 4.) Observe Angel spawn | Angel Object randomly spawns in one out of three places at the start of each round | Angel successfully spawning in one of three places | Pass |
|---|---|---|---|---|---|
| GDM-008 | Destroying Angel Encounters | 1. Choose "Maze Game" from Arcade 2. Select Play. 3.) Locate Angel 4.) Press space 5.) Observe | Angel is destroyed and adds one extra point to the player's score | Angel successfully destroyed and added point | Pass |
|---|---|---|---|---|---|
| GDM-011 | Tickets calculated by score | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3.) Kill 5 enemies 4.) Let the player game over 5.) Calculate 2 tickets | Tickets are calculated by the number of enemies killed divided by two and floored | Tickets are successfully calculated and stored in inventory | Pass |
|---|---|---|---|---|---|
