###Test case documentation for Combat specifically###

##TEST CASES FOR HORSE BOSS BATTLE##
| ID | Test case | Steps | Expected result | Actual result | Status |
|---|---|---|---|---|---|
| CMB-001 | Enemy encounter: choosing option "fight" triggers successful fight sequence | 1. Choose "Fight" option 2. Select Attack, attack goes through | Game transitions into fight scene | Game properly triggers fight scene | Pass |
|---|---|---|---|---|---|
| CMB-002 | Enemy encounter: choosing option "flight" triggers successful flight sequence | 1. Choose "Flight" option 2. Player can run from battle | Game transitions into "flight" scene | Game properly triggers "fight" scene | Pass |
|---|---|---|---|---|---|
| CMB-003 | Flight scene gives player item "record 3" | 1. Successfully run away from battle 2. Game says record 3 is added to inventory | Record 3 is available in inventory after flight scene | Record 3 is in inventory | Pass |
|---|---|---|---|---|---|
| CMB-004 | Basic attack reduces enemy HP correctly | 1. Enter combat and select attack option 2. Observe enemy HP after action resolves | Enemy HP is decreased by the player's "attack" strength | Enemy's health decreases as expected | Pass |
|---|---|---|---|---|---|
| CMB-005 | Enemy attack reduces Player's HP correctly | 1. Enter combat and fail to "dodge" attack 2. Observe player HP after action resolves | Player health should reduce by the enemy's attack strength (20) | Player's HP is reduced by 20. | Pass |
|---|---|---|---|---|---|
| CMB-006 | Consumable item restores health buff correctly (figs, bread, milk, olives) | 1. Enter combat and press "ITEMS" 2. Choose a consumable with a health buff and use it 3.) See if player health is increased | Player health should increase by the item's health buff | Player's HP is increased as expected | Pass |
|---|---|---|---|---|---|
| CMB-007 | Consumable item restores attack buff correctly (figs, milk, cricket) | 1. Enter combat and press "ITEMS" 2. Choose a consumable with a strength buff and use it 3.) See if player strength is increased | Player strength should increase by the item's attack buff | Player's strength is increased as expected | Pass |
|---|---|---|---|---|---|
| CMB-008 | Enemy turn is triggered after every player action | 1. Enter combat and press any action 2. Observe if enemy attack starts | After each action, no matter what it is, the "word scramble" section should pop up for the enemy's turn | Enemy's turn is triggered correctly | Pass |
|---|---|---|---|---|---|
| CMB-009 | Distortion should change fight states if reaching over 3 | 1. Enter combat and ATTACK 3 times in a row 2. Observe the distortion level increase by 3. Observe if > 3 distortion level changes visuals of fight | If distortion levels > 3, fight should enter phase 2 | When distortion level > 3, fight enters phase 2 | Pass |
|---|---|---|---|---|---|
| CMB-010 | If the enemy's health bar is <= 0, end fight and display player as winner | 1. Defeat the enemy in combat 2. Exit combat 3. Observe next scene | The "You win" scene should play if player defeats Horse | Win scene is displayed properly | Pass |
|---|---|---|---|---|---|
| CMB-011 | If the player's health bar is <= 0, end fight and display player as loser | 1. Fail to defeat the enemy in combat 2. Exit combat 3. Observe next scene | The "You lose" scene should play if the player loses against the Horse | Loss scene is displayed properly | Pass |
|---|---|---|---|---|---|
| CMB-012 | Enemy drops proper loot and lore-item after defeat | 1. Defeat the enemy in combat 2. Exit combat 3. Observe item achievements | Both "Record 3" and "Cricket" should appear after defeating the enemy | "Record 3" is dropped, but "Cricket" is not | Fail |
|---|---|---|---|---|---|
| CMB-013 | Story returns to proper state after combat is finished | 1. Exit combat 3. Observe the act number | Once exiting the boss fight with Horse, the act should be 2 | Act properly progresses to 2 | Pass |

##TEST CASES FOR ANGEL BOSS BATTLE##
| ID | Test case | Steps | Expected result | Actual result | Status |
|---|---|---|---|---|---|
| CMB-014 | Enemy encounter: Start Angel Fight | 1. Choose "Show Her" option 2. Select Attack; attack goes through | Upon pressing "Show her" button, fight initiates | Game properly triggers fight scene | Pass |
|---|---|---|---|---|---|
| CMB-015 | Basic attack reduces enemy HP correctly | 1. Enter combat and select attack option 2. Observe enemy HP after action resolves | Enemy HP is decreased by the player's "attack" strength | Enemy's health decreases as expected | Pass |
|---|---|---|---|---|---|
| CMB-016 | Enemy attack reduces Player's HP correctly | 1. Enter combat and fail to "dodge" attack 2. Observe player HP after action resolves | Player health should reduce by the enemy's attack strength (20) | Player's HP is reduced by 20. | Pass |
|---|---|---|---|---|---|
| CMB-017 | Consumable item restores health buff correctly (figs, bread, milk, olives) | 1. Enter combat and press "ITEMS" 2. Choose a consumable with a health buff and use it 3.) See if player health is increased | Player health should increase by the item's health buff | Player's HP is increased as expected | Pass |
|---|---|---|---|---|---|
| CMB-018 | Consumable item restores attack buff correctly (figs, milk, cricket) | 1. Enter combat and press "ITEMS" 2. Choose a consumable with a strength buff and use it 3.) See if player strength is increased | Player strength should increase by the item's attack buff | Player's strength is increased as expected | Pass |
|---|---|---|---|---|---|
| CMB-019 | Enemy turn is triggered after every player action | 1. Enter combat and press any action 2. Observe if enemy attack starts | After each action, no matter what it is, the "word scramble" section should pop up for the enemy's turn | Enemy's turn is triggered correctly | Pass |
|---|---|---|---|---|---|
| CMB-020 | Distortion should change fight states if reaching over 3 | 1. Enter combat and ATTACK 3 times in a row 2. Observe the distortion level increase by 3. Observe if > 3 distortion level changes visuals of fight | If distortion levels > 3, fight should enter phase 2 | When distortion level > 3, fight enters phase 2 | Pass |
|---|---|---|---|---|---|
| CMB-021 | If the enemy's health bar is <= 0, end fight and display player as winner | 1. Defeat the enemy in combat 2. Exit combat 3. Observe next scene | The "You win" scene should play if player defeats Angel | Win scene is displayed properly | Pass |
|---|---|---|---|---|---|
| CMB-022 | If the player's health bar is <= 0, end fight and display player as loser | 1. Fail to defeat the enemy in combat 2. Exit combat 3. Observe next scene | The "You lose" scene should play if the player loses against the Angel | Loss scene is displayed properly | Pass |
|---|---|---|---|---|---|
| CMB-023 | Game State Switches to cutscene after battle | 1. Defeat the enemy in combat 2. Exit combat 3. Observe cutscene | "Record 4" Cutscene should play automatically after defeating the enemy | Cutscene plays successfully | Pass |
|---|---|---|---|---|---|
| CMB-024 | Story returns to proper state after cutscene is finished | 1. Exit combat 3. Observe the act number | Once exiting the boss fight with Angel, the act should be 3 | Act properly progresses to 3 | Pass |
