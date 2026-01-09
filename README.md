# Ang1TestDocumentation
This repository is for testing documentation on the main features of Angel, as well as compiling future bugs/logic issues that beta testers bring to attention.

**Game Overview**
Engine: Ren'Py (Python)
Genre: Psychological horror combining classic visual novel with turn-based combat and minigames.
Platforms: PC
Key Systems:
- Dialogue and choice branches
- Turn-based combat systems
- Varying minigame logic
- Save/load systems (Ren'Py integrated)

**Testing Objectives**
The primary testing objectives for this game are to:
- verify the accuracy and stability of custom minigame systems
- verify the accuracy of unique combat systems and their interaction with the Ren'Py game engine
- ensure core game necessities interact as expected with custom additions (save/load/pause reliability)
- identify game-breaking bugs and state inconsistencies
- assess user experience and player edge cases

**Testing Scope**
All tests in scope will include the combat mechanics, combat state transitions, minigame functionality, and testing built-in functions in these states (save/load/pause).

The tests will not cover changing the internal implementation of the Ren'Py engine or testing cross-platform implementation. The purpose of these tests is not for optimization as of yet.

**Test Approach**
The game will leverage Manual testing to reflect the nature of the interactive, story-based game. Testing will focus on state transitions, unreliable automation, and overall player actions, both those within expectation and edge cases.

Automated testing will be implemented in the future for combat calculations and minigame scoring logic.

**Test Environment**
The operating system will be Windows 10/11, on the current version of Ren'Py. 

**Entry and Exit Criteria**
Entry criteria are that there is:
- Testable minigames and combat systems
- Testable core gameplay mechanics
Exit Criteria, therefore, includes:
- Documented and addressed main bugs
- Core gameplay mechanics working as expected

**Deliverables**
The deliverables will include a list of documents on GitHub that address each problem individually. These documents are:
- combat-tests.md: This document will cover all the manual tests for combat testing.
- minigame-tests.md: This document will cover all the manual tests for the minigame logic and functionality.
- save-load-tests.md: This document will cover all the manual tests for the save/load functions, as well as pausing mid-game.
- bugs.md: This document will contain a master list of every bug found, both on the development team's end and through beta testers.
- bld-verif.md: This document will contain a build verification checklist for any new game builds.

The documentation will be a mixture of text descriptions and visual screenshots of the game.

**Constraints**
This game is a solo-developed project with limited test environments.
The documentation will focus on keeping a record over time, and therefore is not an exhaustive coverage of the testing.

This plan will be updated as new features or bugs arise.

**Prepared By**: Mishtee Shaw.
