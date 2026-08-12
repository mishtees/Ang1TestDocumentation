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
|---|---|---|---|---|---|
| GDM-010 | Player death | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3.) Allow 10 enemies to hit the bottom of the screen | "Game Over" sequence initiated and game state transitions to end loop | Minigame successfully ended | Pass |
|---|---|---|---|---|---|
| GDM-011 | Tickets calculated by score | 1. Choose "Galaxy Dame" game from arcade 2. Select Play 3.) Kill 5 enemies 4.) Let the player game over 5.) Calculate 2 tickets | Tickets are calculated by the number of enemies killed divided by two and floored | Tickets are successfully calculated and stored in inventory | Pass |
|---|---|---|---|---|---|
