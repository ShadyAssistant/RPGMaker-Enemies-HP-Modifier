# RPGMaker-Enemies-HP-Modifier
A simple tool to rebalance unbalanced games made using RPG Maker, by changing enemy HPs in bulk.

## About The Tool

It's [*Fear and Hunger*](https://store.steampowered.com/app/1002300/Fear__Hunger/).
I made this tool because I'm frustated with that game.
I spent 10 minutes to make this tool and used it to reduce all enemy HPs to 1% of their original values, and still loses many times
because I keep playing it with the mindset of a standard RPG player. I hate that game and I'm pretty sure the feeling is mutual.

I haven't tested this tool with other RPG Maker games,
but I'm pretty sure RPG maker games are using similar data structure, so it should work the same.

## How To Use
1. Open pincone-pig-god.html on your browser.
2. Select `Enemies.json` from inside your game. (usually located at `/www/data/`)
3. Determine how much (in percentage) your enemies HP should be.
4. Click "Generate JSON".
5. (Recommended) Back up the original `Enemies.json`.
6. Move the downloaded file to the respective folder.

## Warning
Modifying game files may result in unexpected behaviour in the game. Do it at your own discretion.

## Changelog
- v0.1: Initial Release
