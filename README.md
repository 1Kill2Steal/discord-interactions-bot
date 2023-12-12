# **THIS IS MY FIRST DISCORD BOT**

Planning to make even more commands in the future, feel free to tell me suggestions (discord: 1killsteal)

## CURRENTLY AVAILABLE INTERACTION COMMANDS:
### ALL THE COMMANDS ARE DECLARED IN `src/register-commands.js` AND USED IN `src/index.js`
* **QUOTES**
 * `/quote`                     | **1 OPTION:** "quote_number" *(optional)* - Uses the numbering from `/quotelist`
 * `/quotelist`                 | **8 for now**

* **USER INTERACTIONS**       // FOR ALL: **1 OPTION:** "user" *(REQUIRED)* - Specifies the user to do the action to.
 * `/tieup`
 * `/hug`
 * `/pat`
 * `/kiss`
 * `/slap`
 * `/punch`
 * `/bonk`
* **ALL USER INTERACTIONS HAVE "!" (EXCLAIMATION MARK) ANALOGUES IN CASE YOU WANT TO DO THE INTERACTION WITH A REPLY TO THE USER**
* **EXAMPLE:** `!pat` *(in a message reply with the mentioned user)* works.

Made this bot for a discord server: https://discord.gg/nopengoo


**IF** anyone wants to learn how to make a discord bot then feel free to check this [tutorial video for reference](https://www.youtube.com/watch?v=KZ3tIGHU314).
To make the bot work on your end you need to get nodejs and npm alongside some npm packages: nodemon & dotenv.
You need to make a .env file containing your bot token and then tweak some bot settings and so on.