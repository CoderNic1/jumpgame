Jump and collect game by _Nicholoco

General game information:
We all know the classic platform game, people love it and play it, but now we change it and bring it to a higher level, with elements that are used in the current game world, having competitive elements, ways to let users come daily, have a chance to customize, play free but also spend PLAI to earn more. All is covered by a in-game economy to ensure that we can’t loss on it that people who spend fuel the ecosystem.

Different menus/buttons explained
Login menu
At the beginning a user will see a menu to connect there wallet or buy PLAI on base, there is also a disclaimer (which will change with future updates) and some basic version information.
Main menu
After successfully connecting the wallet and login the user will see the main menu containing multiple buttons which bring them to other menus, those menus are accessible on pc but also on phone.
8 different buttons, those buttons will open a new menu bringing you to other places in the game.

Different game features 
Main game
A user will have to jump by clicking the screen to collect coins, during this jump journey a spike might come along, if a user hits this they loss 20s of time. During the game more elements like a magnet or clock can pass around (premium items). Also a gift might appear wich can be taken by the user to win GOLD and even PLAI (rare chance it comes, users can spend PLAI to let it come faster.)
Shop 
The place to spend gold and PLAI for premium upgrades.
Leaderboard
A weekly leaderboard paying out the top 10 users with $PLAI from the pool, you can also see previous week leaderboard.
Skins
Skins are a way to customize your experience, you can change the player color, background color and skin effect
Game vault
Transparency is important for me, for that reason users will be able to see and know what currently is available to win.
Jump pass
Users can earn XP by doing daily and weekly tasks, these XP will unlock different tiers of rewards, users can also spend PLAI to buy a premium pass giving more and better rewards.
Boosters
Boosters can be earned only in the pass (for now) and gives them a boost during playing
PLAI 
Users can earn PLAI in the pass this comes from the pass poo in the vault
Skins
Users (premium) can earn exclusive background and skins, more plans for this.
Spin tickets
Users can earn spin tickets on the free and paid road, this can be used to win nothing, gold and PLAI
tasks
Users can do daily and weekly tasks helping them to proceed in the jump pass.

Important functions inside the code explained
Function spendPLAI
This function will check and distribute the PLAI to the pools, its a centralised function for any PLAI spent in the game.
Function Savedgamedata
This function will save all player based gamedata, for now keep in mind the leaderboard isn’t fully saved yet

Data saving
For now all the playerdata is saved locally on the user web browser and not per session, in the past it was an issue but I have successfully changed this to make sure it saves.

A wallet connect is available wich lets a user create a username in the future we might change this to avoid wrong names are used.

Current issues/bugs/dangers
Game UI phone
The current UI for on phones isn’t always well optimized, different fixes have been deployed but no success currently.
Danger Pass, weekly tasks and leaderboard
There was a bug where the weekly tasks and leaderboard didn’t reset at the end of the week, this should be fixed but hasn’t been tested yet because we aren’t a week further yet. The pass reset hasn’t been tested at all yet
Spin the wheel UI
Diffrent changes has been done but currently the UI of the spinning wheel isn’t great yet

Future plans
Make the pass have different variations every month
Add a “pass vault” when a users who is premium reached the end of the pass eacht extra 50XP earned will give 1 spin ticket
Make it possible that some skins/effects give bonuses in the game
Add better skins (such as zombie skin, chocolate skin, animal skin etc) and better quality backgrounds and not just a color.
Add a shop section to buy a few boosters with coins/PLAI
Review the coin costs of the current upgrades and rebalance them
Add a function to payout the developer share every week.
If needed add a deposit/withdraw PLAI system instead of automatically direct on-chain actions for every spend/earn

Ecosystem explained
Main ecosystem
20% for leaderboard pool.
25% for the game play pool (win $PLAI by playing).
15% for "Jump Pass" shared with everyone reaching the end.
      40% for developers for further development.

Spin the wheel ecosystem
40% nothing
40% gold
20% PLAI

Disclaimer and credits
The current version is still a wip, I am not liable for any issues caused by the code, the game or this file. Play and use at own risk.
