###Masterlist of bugs ###

## BUG-001: Inventory does not save upon reloading old save files
**Severity:** High
**Status:** Closed
**Found in:** LD-002

**Description:** After the player returns to the game to load the file, the inventory is not saved properly.

**Steps to reproduce:**
1. Save with items in inventory
2. Exit game
3. Load into save file
4. Observe inventory

**Expected:** Inventory should save items pre-exiting the game
**Actual:** Inventory is lost.

## BUG-002: Overlapping sprites in FIGHT animation
**Severity:** Medium
**Status:** Closed
**Found in:** cmb-003

**Description:** Player's attack animation overlaps with the static sprite.

**Steps to reproduce:**
1. encounter combat
2. press attack

**Expected:** Player attack animation should play and then return to the static sprite.
**Actual:** Static sprite remains underneath animation, so they overlap.

## BUG-003: If you lose Angel’s fight, you’re taken back to the main menu
**Severity:** Critical
**Status:** Closed
**Found in:** CMB-010

**Description:** After the player loses to Angel, instead of the fight restarting, they are returned to the main screen of the game

**Steps to reproduce:**
1. Lose Angel fight

**Expected:** Player should see a retry button and be redirected to the start of the fight.
**Actual:** Player is immediately returned to the main menu.

## BUG-004: Sequence of scenes leads to a major game glitch when exiting "Rules" screen for "Galaxy Dame" minigame 
**Severity:** Critical
**Status:** Open
**Found in:** Beta Tester

**Description:** When player specifically goes from "extra questions" screen, to Galaxy Dame's 'rules' screen, and then attempts to press "back", screen lags out and goes through a series of glitching scenes before it returns to the arcade.

**Steps to reproduce:**
1. Press "go back" in arcade
2. Ask Angel or Horse a question
3. Return to the arcade and press Galaxy Dame machine
4. Press "rules" on the machine and then attempt to press "back."

**Expected:** Player should be returned to the arcade immediately
**Actual:** Player is taken through a series of glitches, including glitching to the claw game before it returns to the arcade.

