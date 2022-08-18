# ShieldMaidens_PatchNotes


### v0.5.5 patch notes [July 03, 2022]
- Online PvP is here! Please note it's very alpha-stage but you can now host games and join using a shared code thanks to Unity's new relay service.
  - Host games button allows you to act as the server & client, the join code will be visible on the UI for sharing
  - To join a game input the join code and his Join, this will attempt to connect to the host's game and spawn you in if successful
- Updated project to Unity 2021 and made lots of run-time performances changes in the codebase
- Bug where the gold reward dialog would appear before interacting with chest now squashed
- Bugfix to allow open and closing the caravan traders with the same btn on a controller

---

### v0.5.4 patch notes [February 21, 2022]
- Every run you play will now randomly pick a different skin for your shield
- Prefer only using a shield? Now you can select it from the loadout and carry a slightly larger one!
- Kraken map overlapping the cave bug has been fixed
- Added a back button to the LAN menu
- Arrows stuck in your shield disappear when thrown

---

### v0.5.3 patch notes [January 19, 2022]
- Elf wizards have began emerging from the forest. They cast unpredictable projectiles that move in a sine pattern and follow you until something blocks them!
- A timer has been added to the top right of the UI during pillages so you can see how long you've survived so far.
- Expanding on that timer - there's a new scoreboard to keep track of your best runs. Best score are the ones where you killed the most bosses in the least time
- Once you've defeated all current bosses, you'll be presented with an end-game screen to congratulate you on a successful run!
- Removed knockback from some enemies and projectiles to avoid flying across map when dashing as this happens
- UI accessibility improvements
- Lots of bug fixes

---
### v0.5.2 patch notes [December 30, 2021]
- A new loadout menu in the starting scene
- Bows are now a secondary option in the demo
- New runes added and available to choose from:
  - Surtr rune makes your dash go further and damages enemies you pass through
  - Valkyrie rune gives you wings to triple jump
  - Svalinn rune lets player summon a huge static barrier to protect them for 5 seconds
- The Svalinn rune has an icon in the top left of the UI below your info to show when you can use it again
- Hitting enemies with a projectile now shows a collision animation
- Goblin archer towers a little higher and targets made bigger too!
- Drawn a new shield as the original was from an asset pack I never got round to changing
- The settlement area has been removed from the core game, partly since the scope was getting out of hand again, but also because I want to put more energy into the core mechanics that make it fun to play in both single player and co op

---

### v0.5.1 patch notes [December 26, 2021]
- Goblin caves will now randomy appear on your pillages. The ground scouts are quick, but goblins are also pretty sharp with a bow
- Number of players will now be selected before entering a pillage, and keyboard/gamepad can be switched from the Controls section under the pause menu
- Potions that dropped from enemies in lighthouses couldn't previously be reached - so no you can collect them by throwing your shield at them
- The Kraken has been revamped & made easier, their tentacles are now your main target, health has been lowered and one of the archers has handed in his resignation!
- Alchemist is now a little slower at throwing bombs
- Screen shaking! Now you'll really feel (or think you did) when the tentacles slam down on the boat
- If you run too far backwards on the map you'll be blocked and see a warning message saying you've gone too far.
- UI tweaks and icons added
- Bugs:
  - Alchemist tank now can not be hit until scene starts
  - Knights disappearing behind cave entrances fixed
  - NPC's cant be hurt twice by same shield
  - Boss list refreshes if all bosses cleared

---

### v0.5 patch notes [December 20, 2021]
- Your shield can now slot 3 runes, as more runes are added to the game you will have to decide which 3 to take on your adventures 
- Mischief rune: when equipped, it has a different special trigger effect for each weapon
  - A bow will trigger a chance to shoot mischief magic whichever way you aim
  - Swords will extend your reach, dealing more damage and hitting multiple enemies further away
  - Your shield will have a chance to conjure a magical shield to replace it upon hitting enemies
- Pause menu will show currently equipped runes, hover a rune for more info
- LAN test mode available, you can play around and fight locally without runes
- 2 new scenes for the randomly generated pillage, both newly drawn:
  - The first being a cave where you need to dodge falling stalactites, but with plenty items to be found! 
  - The second being spiked barricades where you'll need to carefully jump and dash across to avoid falling into them
- Health potions give x2 more health (+30 now)
- Enemies now drop items rather than them appearing around the world
- You can jump whilst in water so you can't get stuck anymore
- Mural tower made easier to jump over and co op max distance increased after watching some live test gameplay
