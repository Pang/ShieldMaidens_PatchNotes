# ShieldMaidens_PatchNotes

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
  - NPC's cant hit hurt twice by same shield
  - Boss list refresh if all cleared

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

---

### v0.4.9.5 [November 22, 2021]
- Players can now customize their appearance at their settlement homes! This includes Skin tone & changing hairstyles / wearing helmets.
- Rune-crafter buildings can now be placed in settlements. You won’t find runes in travelling caravans anymore but their effects will now work with all secondary weapons as well as your shield!
- Major animation overhaul, player attacks, abilities, spells. Bosses have also had their abilities and scene animations updated
- A reward chest will summon itself at the end of a boss fight which you can pick up! This was a better experience than having 100 gold coins flying your way - plus they may contain other rewards in future.
- Blacksmiths will now sell secondary weapons rather than health/dmg upgrades. Your secondary slot can be switched at the player's home.
- Forest trees & clouds have been redrawn & digitally painted, the river scene has been updated alongside this.
- Settlement has moved around, you’ll now find your workbench and questboard in the middle
- Lots of bug fixes like player arrows sprite layer rectified, shield won’t go under the map anymore, camera focus improvements in boss fight scenes and arrows shouldn’t bounce off invisible walls anymore
- Online beta will allow you to host from your own computer, the host will need to share their IP to the person they wish to play with but leaving the address box empty will join anyone hosting on the same LAN. This is currently a work in progress and not fully implemented!
- Minor performance improvements & health bar now more visible on player/npcs

---

### v0.4.9 [October 26, 2021]
- Improved overall visuals with a terrain sprite, fog in the background & clouds
- Added a 2h sword as a secondary weapon choice. This weapon can deflect projectiles and hit mutliple enemies
- The home is now interactable and has a menu to switch your secondary weapon
- krakens health slightly lowered
Note: Rest of player customizing will be released in v0.4.9.1

---

### v0.4.8 [October 11, 2021]
- The Kraken has been released! A fourth boss has been added into the mix but this time you're fighting it from a boat
- A bow has been added to your arsenal, hold down to aim - release to let go!
- You can now switch between weapons as long as your shield isn't flying across the map
- The artstyle has changed and is now 2.5d! (whatever that means)
- Enemy Archers have been to a shooting bootcamp and are much more careful with their aim
- Lots of refactoring. Player scripts in particular so that weapons can be swapped in & out
PS: A quick tip for this boss-fight, deal with the archers on the lighthouses first :)

---

### v0.4.7 [September 26, 2021]
- Background separation, re-drawn the hills with plenty trees and placed them in the back to create more parallax.
- Save slots can now be deleted. Confirm dialogs will appear so you don't accidentally hit the delete button
- Whilst playing co-op, dead players will now be revived at camps so you can continue your journey together
- Changes to the building, stores and game mode user interfaces to be more user friendly!
- There are now 2 modes instead of 3 (Normal/Expert). You may need to delete your previous saves but you get 1000g for free on new game
- A hole has been drawn and placed around the mage tower, doesn't just appear to be floating out of nowhere anymore!
- Lots of refactoring enemy scripts and base classes etc (Meaning I can expand the array of hostile enemies and bosses more efficiently)
- Bosses can no longer be affected by rune specials

---

#### v0.4.6.1 [September 16, 2021]
- More in-game sounds added (inc: all boss fights) and improved previously added sounds. Scene music also made quieter.
- Added camera focus points during boss fights, This is to indicate to the player that these are significant events
- Adjustments to how the camera follows you, the y-axis is no longer dead-zone but has a soft follow instead.
- DeltaTime and frame issues no longer affecting speed of boss fights
- Added an exit button to main menu (where load slots are) so it's easier to find

---

### Version 0.4.6 Notes [September 10, 2021]
- 2 Compositions added, one for the opening and pillage scene, the other more relaxing to fit your settlement!
- Sound effects for hitting enemies, blocking arrows, picking up and using pots now in the game. There's also mute button on the pause menu just incase you want to listen to your own music ;)
- The opening scene has now been animated, watch the shield fly in whilst the text pulses to the music
- Collecting items now triggers a +1 floating animation above the player and using those items will light up the player with the color of the potion consumed
- If item capacity limit is reached, you'll auto-consume instead of picking up. The UI has been updated to display max-capacity of items
- Since there's currently one level, the map will display a "Pillage!" button in the top right instead of quest markers to not confuse new players during alpha
- Arrows no longer bounce off your shield but stick into it for a short while, the physics of them bouncing off made no sense previously
- Re-interacting with Eovir caused an event delegate issue which is now fixed, 
- Clicking exit on menus wont make you throw your shield anymore and trade caravans/apothecary potion numbers are synced properly
- Small changes to general UI, menus & text

---

#### v0.4.5.1 [August 21, 2021]
- Some player camera follow changes in settlement & pillage mode. Made distance of FoV larger.
- Code to make sure a camp will definitely spawns after a boss, as  sometimes this didn't happen
- Caravan errors looking for missing items have been fixed
- Couple little co op bugs sorted

---

### Version 0.4.5 Notes [August 20, 2021]
- The wall jump mechanic has been removed. Having a double jump made wall jumping excessive and having some walls be climbable and others not was actually just inconsistent & annoying to players. If you're struggling to get over the keeps - try jumping on something else first :)
- Co op is back, you can enable/disable from the settlement from now on. So remember to enable before you head out on a mission with a friend!
- Potions are now kept on you instead of being instantly consumed, you can press the keys 1 & 2 or up/down on a D-Pad. The shop has also been updated to sell potions to take with you.
- Controls list now accessible through the pause menu
- A couple more buildings have been added, but these ones will cost gold:
  - A Blacksmith can be purchased for your settlement, you will now get health and shield upgrades from there instead of the caravans
  - An Apothecary can also be bought and built, potions can be purchased here for a little less gold than caravans!

---

### Version 0.4.4 Notes [August 15, 2021]
- You now have a settlement! Starting the game will spawn you there and it will act as your hub
- Settlement building functionality is now in-game. It's currently in a prototype stage but more buildings will be added in the next few versions to aid you on your missions! Just go over to your building bench to get started
- The world map can be found in your settlement and you can select missions by interacting with the questboard
- Eovir is a friendly NPC that will be your trusty advisor and is the first NPC with dialogue! You can interact with him again incase you accidentally skipped
- Camps now spawn right after a boss so you can continue your journey after a hard battle. Any other chance of a camp spawning is now 1 in 6.
- Redesign on the background again, your settlement has it's own variation too
- Side note: Couch co-op has been frozen as I'm currently reworking it, thanks for your patience!

---

### Version 0.4.3 Notes [July 20, 2021]
- The Sorcerer's tower has been revealed, seek her out before she becomes too powerful! Wait for the time to strike, she has her shield up whilst she fights, but becomes vulnerable when summoning allies.
- The Alchemist has been buffed, their poison now does more than x2 more damage and the tank has twice as much health
- The Berserkers walls have been fixed so you dont get stuck on them, also added spikes to make it clear you can't climb them. But don't try - you might just hurt yourself
- During one pillage play-through, bosses will no longer appear again until all other bosses are defeated.
- Scenes now look like you're running through a forest! The current assets are a placeholder until I start the asset redraw phase
- Potions and Coin sprites now glow & are brighter so they stand out more
- Small bugs like the mage's shooting direction lag has been fixed, and archers wont try shooting you through walls anymore

---

### Version 0.4.2 Notes [July 10, 2021]
- The Berserker pit has been implemented into the game, now you'll have to fight him in his own home!
- The Berserker now has solid lines and has been coloured in to show off his golden headgear.
- He's also been given particle animation, which triggers to show the area of damage from his leaping strike.
- Enemies now flash red to indicate that you've hit them
- Your thrown shield will no longer collide with enemies on return. This is to stop it getting stuck too often.

---

### Version 0.4.1 Notes [July 01, 2021]
- The Berserker has been introduced, keep your distance and dodge those leaping strikes by dashing!
- Player now flashes red when damage taken.
- Player will no longer collide with enemies, meaning you can run through/past them.
- You can now dodge melee attacks (try dashing) before their melee animation hits you.
- Enemies with armor can no longer be knocked back.

---

### Version 0.4 Notes [June 09, 2021]
- ShieldMaidens first boss *The Alchemist* has been introduced! Watch out for poisonous toxins coming through the pipes and be ready to destroy its source by using The Alchemist's own weapons against them. But be careful, once you enter their lair - there's no way out until you make one!
- The Alchemist's chance to appear will increase once you pass your first camp. This is the first boss in the game so they'll likely appear a few times if you play long enough, plans to introduce more will be revealed soon.
- Updated the archer tower, redrew and colored it with perspective as well as splitting the front/back assets to make it interact like a 3d space with the archer inside.
- Co-op can now be enabled/disabled in-game from the pause menu.
- Number of pillage scenes until player camp appears has been reduced.
- Camera Y dampening removed due to getting stuck quite low after coming out of water. Camera Y position also altered so player is still looking relatively close to center of screen when following character whilst still being able to see above archer towers.
- Timer for destroying dead enemy GameObjects reduced from 3s to 2s.

---

### Version 0.3.5 Notes [May 11, 2021]
- Old game menu removed and opening menu scene redesigned.
- For saving progress you will find camp sites every so often that auto-save the game.
- The shop will no longer be on the main menu, to spend your gold you'll now find travelling caravan at camp sites.
- Old generated map parts now get destroyed after set distance reached, this also applies to enemies
- Reanimated the fire
- Mages fireball speed increased but longer cast time
- Worked on the visuals by creating 'perspective' such as the angle you see some buildings which now look "3D". Alongside this removed the middle parallax layer.

---

### Version 0.3.2 Notes [May 01, 2021]
- Redrew the background hills in pillaging mode
- Fixed the collider on the knight
- Removed camera lookahead, was hard to see what was happening on screen when turning
- UI changes to Opening scene
- UI changes to shop
- Fixed road perspective

Spent the last week researching hex-tilemaps as an open world map option but the implementation I had in mind would bring a huge scope creep.
Will continue looking into other options to expand the world

---

### Version 0.3.1 Notes [Apr 21, 2021]
- Archer and crossbow reskin
- Knight reskin
- Knight animations, walking & swinging sword
- Knight now takes less damage due to armor
- Menu redesign
- Camera movement changes

---

### Version 0.3 Notes [Apr 16, 2021]
- Save slots & difficulty levels implemented
- New Menu and dialog for selected No of players
- Upgrade shop to spend your gold
- Mage reskin
- Mage animation for casting fireball
- Ability upgrades and their animations
- Player 1 can now use Mouse/Keyboard or Gamepad
