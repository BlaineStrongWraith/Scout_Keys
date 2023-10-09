Goal: Farms Polygon in Catmandu
Location: Mooshu - (Panda Mount) - Catmandu
- This is an old program I made some time ago just changed to polygons. Please read carefully.
- This can run on 4 ACCOUNTS at the same time.
- Wooden chest config value can only be spelled 'True' without the  during config, anything else would make wooden_chest config into False.
- Wooden chest will provide aura tc, misc reagents, and gold, however, will waste more time in finding OOA resources.
- Separate page config from each player if possible if running with multiple accounts for a greater yield of resources. Given the time frame, some clients may overlap because of async.sleep(n) after a few hours.
- You cannot be in the configured realm when running the program, e.g., if player1_realm is set to Diego and player1 is in Diego realm when you run the program, it will not run. Swap to a different realm and restart.
- A spelling mistake in the player(n)_realm will freeze the program. Capitalization does not matter.
- The maximum number of clients supported by this program is 4. Any more will overlap each player.
- Do not invite each client into the same group. Wiz client will automatically put you in the same realm as one another when swapping areas.