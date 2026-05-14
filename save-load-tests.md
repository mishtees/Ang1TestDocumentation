###Testing basic save/load functions interact as expected from Ren'py even in high-risk environments.
| ID | Test case | Steps | Expected result | Actual result | Status |
|---|---|---|---|---|---|
| SV-001 | Save in the middle of a dialogue sequence | 1. Enter dialogue 2. Save | Save should save mid-sentence of the dialogue | Save successful | Pass |
|---|---|---|---|---|---|
| LD-001 | Load into previous save file after progressing significantly | 1. Play minigames 2. Load old save file | Should load to previous game state with no minigame data or loot saved. | Load successful | Pass |
|---|---|---|---|---|---|
| LD-002 | Able to load save file after quitting the game and returning | 1. Save file 2. Exit game 3. Load file | Load should return to the same game state, inventory state, and health that was before | Load successful, but inventory is lost | Fail |
