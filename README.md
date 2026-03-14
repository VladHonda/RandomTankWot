# RandomTankWot
When you don't know what tank to play. Run this and it will show what tank to play with the winrate below 50% so you have a chance to fix your winrate and not wreck the winrate of other tanks.

You only need to get your World of Tanks Api key and also your ingame name.

Steps to get a World of Tanks API key

Go to the Wargaming developer portal
https://developers.wargaming.net

Log in with your Wargaming account (the same account you use for World of Tanks).

Open Developer Room.

Click “Add Application”.

Fill in the form:

Application name – any name (e.g., MyWoTStatsApp)

Platform – choose Web / Desktop / Other

Redirect URL – you can use something simple like http://localhost

After submitting, you will receive an Application ID.

Example API key

It will look something like this:

application_id=1234567890abcdef1234567890abcdef
Example API request

You can test it with a simple request:

https://api.worldoftanks.eu/wot/account/list/?application_id=YOUR_APP_ID&search=playername

This returns player data in JSON.

✅ Useful endpoints

Player search → /wot/account/list/

Player stats → /wot/account/info/

Tank stats → /wot/tanks/stats/
