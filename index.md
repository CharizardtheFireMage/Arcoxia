This is the current command list for Arcoxia in the Azure Server. 

1v1 Commands
------------
These are some custom commands used to create a tournament in the 1v1 room of the Azure Server. 

- `1v1 [none|doubles]` - The bot creates a 1v1 tournament (Single or Double Elimination). 
- `monoletter` - The bot creates an 1v1 tournament and declares what pokemon of a specific letter to use. 
- `monocolor` - The bot creates an 1v1 tournament and declares what pokemon of a specific color to use.
- `monopoke [name]` - The bot creates an 1v1 tournament and declares what pokemon should you use.
- `monothreat` - The bot creates an 1v1 tournament and declares what pokemon of a specific type to use. 
- `declareletter [letter]` - The bot declares what pokemon of a specific letter that you have to use in the Monoletter 1v1 Tournament. 
- `declarecolor [color]` - The bot declares what pokemon of a specific color that you have to use in the Monocolor 1v1 Tournament. 
- `declarepoke [pokemon]` - The bot declares what pokemon that you have to use in the Monopoke 1v1 Tournament. 
- `declarethreat [type]` - The bot declares what pokemon of a specific type that you have to use in the Monothreat 1v1 Tournament.
- `ovoei [ce1v1|mono1v1rr]` - The bot PMs you with the rules or any information about an 1v1 event. 

For the monoletter, monocolor, and monothreat commands, PLEASE do not spam this command, because that the bot will switch letter, color, and typing every time the command is used. 

1v1 Staff Commands
------------------
- `ce1v1` - The bot creates a 1v1 tournament, addhtmlboxes the rules and a button at which users can press to PM the host for a pokemon. For every 5 minutes for 20 minutes, the bot will auto-addhtmlbox the button to PM the host, so don't start the tournament until after the bot has auto-addhtmlbox'ed four times. Whitelisted users have access to this command. 
- `mono1v1rr` - The bot creates a [Gen 7] Monotype 1v1 Tournament and declares the rules of the event. & and up have access to this command. 

Monotype Commands
-----------------
This is a command that is used for the Monotype room in the Azure Server.

- `monotour [uu|lc|duotype|1v1|aaa|stabmons|bw|ubers|monothreat|catchandevolve]` - The bot creates a tournament and declares what type of tournament is being played right now, as to notify users what teams to use.

Art Profile Commands
--------------------
These commands are applied to setting up an Art Profile or a CSS Profile in the Design Shop. For any help with these commands, please talk to a Room Moderator and up in the Design Shop. 

- `addsprite [basic|recolor|animated|custom], [link]`- Adds the desired avatar, that you have made, into your artprofile.
- `removesprite [basic|recolor|animated|custom], [link]`- Removes the desired avatar, that you have made, from your artprofile.
- `addcss [link], [width], [height]`- Adds a CSS Design that you have made into your cssprofile.
- `artprofile [user]`- Display the art profile of a user, or use artprofile to display your own artprofile.
- `deleteprofile [user]`- Delete the entire artprofile of a specific user (only accessable by the owners of the room).
- `cssprofile [user]`- Display the CSS profile of a user, or use cssprofile to display your own cssprofile.
- `deletecssprofile [user]`- Delete the entire cssprofile of a specific user (only accessable by the owners of the room).
- `showimg [link], [width], [height]`- Broadcasts an image with a set width and height.
- `showavatar [avatarNum]`- Broadcasts a default trainer avatar of choice.
- `imgsearch [pokemon]`- Searches for sprites of a chosen pokemon, if any are available. (Does not cover all artwork)

iLa Commands
-------------------
The commands are used to evaluate and control the leaderboard in iLa. You need t be a Room Moderator and above to have access to the administrative commands.

- `givepoints [user], [points]`- Gives points to an iLa member. @ and up have access to this command.
- `takepoints [user], [points]`- Takes points from an iLa member. @ and up have access to this command.
- `resetpoints [user]`- Resets points from an iLa member. # have access to this command.
- `ilalb` - Displays the iLa Leaderboard in the chat. + and up have access to this command.
- `points [user|none]`- Displays how many points that an iLa member owns. + and up have access to this command.

Wi-Fi Gift Shop Commands
------------------------
The commands are used for hosting giveaways in the Wifi Gift Shop, and is only restricted to this room. Moderator and up only have access to these commands. 

-`giveaway add, [user]` - Adds an user to a giveaway.
-`giveaway remove, [user]` - Removes an user from the giveaway.
-`giveaway join` - Joins the giveaway
-`giveaway leave` - Leaves the giveaway
-`giveaway prize, [prize]` - Sets the prize of the giveaway.
-`giveaway draw` - Begins the giveaways. (Takes two minutes until a lucky winner is decided.

Basic Commands
------------

Basic features and some information about the bot.

 - `about` - Basic bot info, with the link to this repo.
 - `git` - Link to this repo
 - `version` - Bot version
 - `help` - Get a link to this guide
 - `time` - Current time for Bot
 - `uptime` - Time since the last bot restart
 - `seen [user]` - Latest data from an user
 - `alts [user]` - List of known alts of an user (Alts detedted from namechanges)
 - `say [text]` - Force to say something

Dynamic Commands
------------

Dynamic commands are commands saved in a JSON, used for commands that are continuously changing, like forum links or usage stats. Commands for using, creating, modifying and deleting dynamic commands are the following:

 - `dyn [cmd]` - To call a dynamic command
 - `wall [cmd]` - To call a dynamic command (with announce / wall)
 - `temp [text]` - Set temp var, to create a command
 - `setcmd [cmd]` - Create or modify a command, with `temp` data previosly set
 - `setalias [alias], [cmd]` - Set an alias of an existent dynamic command
 - `delcmd [cmd]` - Delete a command
 - `dyncmdlist` - Get the list of dynamic commands

**NOTE:** You can use a dynamic just with `.command` (command character + command name) if there is not another static command with the same name. So you can use this to create only-text commands with ease.

Chat Plugins
------------

Misc commands for multiple features:

 - `pick [option1], [option2], [...]` - Choose between multiple options
 - `randomanswer` - Get a random answer
 - `joke` - Get a random joke from the local database
 - `quote` - Get a random quote from the local database
 - `regdate (username)` - Get the register date of a Pokemon Showdown account
 - `regtime (username)` - Get the age of a Pokemon Showdown account, useful for check if an account is autoconfirmed

Commands for getting pokemon info:

 - `translate [move/item/ability/nature], (source lang), (target lang)` - Command for translating pokemon stuff
 - `poke` or `randompokemon` - Get a random pokemon
 - `gen [poke]` - Get pokemon, item, etc generation
 - `viablemoves [poke]` - Get viable moves from a Pokemon
 - `heavyslam [poke], [poke]` - Get heavyslam base power
 - `priority [poke]` - Get priority moves
 - `boosting [poke]` - Get boosting moves
 - `recovery [poke]` - Get recovery moves
 - `hazards [poke]` - Get hazards moves
 
Smogon-related commands:

 - `usagelink` - Get a link to Smogon official usage stats
 - `usage [pokemon], (tier)` - Get usage stats of a pokemon
 - `usagedata [pokemon], [moves / items / abilities / spreads / teammates], (tier)` - Get usage data (common moves, items, spreads, etc) of a pokemon
 - `suspect (tier)` - Get information about a suspect test
 - `setsuspect [tier], [pokemon being suspected, ...], [link to Smogon]` - Set suspect information
 - `deftier [tier]` - Set default tier for `usage` and `suspect` commands

Commands for managing the local database of jokes and quotes:

 - `addquote [id], [text]` - Add a new quote
 - `delquote [id]` - Delete an existing quote
 - `listquotes` - Upload quotes to hastebin
 - `addjoke [id], [text]` - Add a new joke
 - `deljoke [id]` - Delete an existing joke
 - `listjokes` - Upload jokes to hastebin

Administrative Commands
------------

Commands for controlling the bot and command permissions for chat rooms.

 - `custom [text]` - Send something to current room
 - `custom [room] [text]` - Send something to a chat room. Brackets are obligatory if you specify the room. Example of usage: `custom [lobby] Some text here`
 - `pm [user], [text]` - Send a private message
 - `join [room1], [room2], [...]` - Join chat rooms
 - `leave [room1], [room2], [...]` - Leave chat rooms
 - `joinrooms [official/public/all]` - Join all rooms
 - `lang [lang]` - Set the language of the room
 - `settings [cmd], [rank]` - Configure command permissions
 - `battlesettings [permission], [rank]` - Change permissions for battle rooms

Developing Commands
------------

Commands for developing (only for excepted users)

 - `eval` or `js` - Execute arbitrary JavaScript
 - `send` - Send anything to the server
 - `reload [commands/config/features/laguages]` - Hotpatch source files
 - `updategit` - Fast forward from git repo
 - `clearcache` - Clear the cache, for example for reloading the usage data

CommandParser developing commands

 - `ignore [user]` - Bot will ignore an user
 - `unignore [user]` - Stop ignoring an user
 - `sleep [room]` - Change the room status to `Sleeping`, to disable bot commands in a room
 - `wake [room]` - Change the room status to `Ready`, to re-enable bot  commands in a room
 - `status` or `roomstatus [room]` - Show the current status. Abbreviations: [c - chat, b - battle][r - ready, s - sleeping][Bot group][p - public, h - hidden]. Example: crup = chat, ready, user, private

Commands for terminating the process (for restarting the bot)

 - `lockdown` - Set lockdown mode, use `endlockdown` to revert it
 - `kill` - End the process after using lockdown
 - `forcekill` - Kill the process

Moderation
------------

**Mod Settings:** Use `mod (room - optional), [moderation], [on/off]` to enable or disable moderations.

**Moderation Exception:** Use `modex [rank/all]` to change moderation exception for a room.

**Autoban**
 - `ab [user1], [user2], [...]` - Add users to blacklist
 - `unab [user1], [user2], [...]` - Remove users from blacklist
 - `rab [regex]` - Regex ban
 - `unrab [regex]` - Remove a regex ban
 - `vab` - View blacklist

**Zero Tolerance**
 - `0tol [user]` - Checks if an user is in the zero tolerance list
 - `0tol add, [user1]:[level1], [user2]:[level2], [...]` - Add users to zero tolerance list
 - `0tol delete, [user1], [user2], [...]` - Removeusers from zero tolerance list
 - `vzt` - Upload zero tolerance list to hastebin

**Banwords and InapropiateWords:** Saying this words means automute. InapropiateWords requires that words are separated.
 - `banword [phrase]` - Add a banword
 - `unbanword [phrase]` - Remove a banword
 - `vbw` - View banword list
 - `inapword [phrase]` - Add an inappropriate word
 - `uninapword [phrase]` - Remove an inappropriate word
 - `viw` - View inapropiate words list

**Joinphrases:** Configure what phrase Bot says when certain user joins a room. This can be spammable, much caution!
 - `joinphrase [enable/disable]` - Enable or disable joinphrases for a room
 - `joinphrase set, [user], [phrase]` - Set a joinphrase
 - `joinphrase delete, [user]` - Remove a joinphrase
 - `vjf` - View joinphrases list
 
**Note:** Excepted users can use moderation commands in format `command [roomid]Arguments` to set moderation through PM or other room. Example: `ab [lobby]spammer1, spammer2`

Battle
------------

Commands for battle feature

**Developing**
 - `evalbattle` - Execute arbitrary JavaScript in a battle context
 - `reloadteams` - Hotpatch teams
 - `reloadbattle` - Hotpatch battle modules
 - `move` - Force a custom move

**Challeges**
 - `blockchallenges` - Block Challenges
 - `unblockchallenges` - Stop blocking challenges
 - `chall [user], [format]` - Send a challenge
 - `challme [format]` - Send a challenge to yourself

**Tournaments Joining**
 - `jointours [on/off]` - Enable or disable tour joining
 - `jointour` - Join a tournament
 - `leavetour` - Leave a tournament
 - `checktour` - Check the tournament (If the bot does not challenge or something)

**Ladder**
 - `searchbattle [format]` - Search a battle and returns the link
 - `ladderstart [format]` - Start laddering (checks every 10 seconds)
 - `ladderstop` - Stop laddering

**Teams**
 - `team add, [name], [format], [http://hastebin.com/raw/example]` - Add a team to Bot teams list
 - `team delete, [name]` - Remove a team from Bot teams list
 - `team get, [id]` - Get a team in exportable format
 - `team check, [id], (user)` - Challenge with a specific team
 - `teamslist` - Upload teams list to Hastebin to view it.

Tournaments
------------

Commands for Tournaments feature

 - `tour` - Start a tournament
 - `tour tier=example, timer=30, users=64, dq=1.5, type=elimination` - Start a tournament with custom and optional parameters
  - **tier**: Tournament format / tier
  - **timer**: Max time (in seconds) before starting the tournament
  - **users**: Max number of users (for singups)
  - **dq**: Minutes for autodq
  - **type**: elimination or roundrobin
  - **scout**: set `scout=off` for enabling scout protection
 - `tourhelp` - Help for `tour command`
 - `tourstart` - Force start a tornament
 - `tourend` - Force end a tornament

Commands for leaderboards system

 - `rank (user)` - View users's ranking (points, wins, finals, semifinals, etc)
 - `top` - View the Top5 in the leaderboard
 - `official` - Make a tournament in progress official (to be counted, see config)
 - `unofficial` - Make a tournament in progress unofficial
 - `leaderboards table, [room]` - Upload the leaderboard table to Hastebin
 - `leaderboards reset, [room]` - Reset leaderboards data
 - `leaderboards setconfig, [room], on, [Win points], [Finalist], [SemiFinalist], [Battle win points], [official/all]` - Activate and set leaderboards configuration
 - `leaderboards setconfig, [room], off` - Disable leaderboards system.
 - `leaderboards viewconfig, [room]` - View leaderboards configuration
 - `leaderboards reset, [room]` - Reset leaderboards data

Games
------------

General commands for managing games:

 - `game [Game Name], arg1=value1, arg2=value2...` - Start a game
 - `endgame` - Force end a game
 - `reloadgames` - Alias of `reload feature, games`

**Hangman** and **Poke-Hangman**. Arguments: maxfails (max number of allowed fails, 0 or no specify this argument for infinite), lang (optional only for Poke-Hangman to change the language of the pokemon stuff). Commands:

 - `g [word/char]` - To guess words or characters
 - `view` - To view the game status
 - `end` - To force end the game

**Anagrams** and **Poke-Anagrams**. Arguments: games (max number of rounds), points (number of ponts for winning), time (time to answer in seconds), lang (optional only for Poke-Anagrams to change the language of the pokemon stuff). Commands:

 - `g [word]` - To guess the words
 - `view` - To view the game status
 - `end` - To force end the game
 
**Trivia**. Arguments: games (max number of rounds), points (number of ponts for winning), time (time to answer in seconds). Commands:

 - `ta [answer]` - To answer the questions
 - `view` - To view the game status
 - `end` - To force end the game

**BlackJack**. Arguments: time (time for each turn in seconds), maxplayers (max number of players) Commands:

 - `in` - To join the game. Use `out` to leave
 - `players` - To view the players list
 - `start` - To start the game
 - `hand` - To view your hand
 - `hit` - To get a new card to your hand
 - `stand` - To finish your turn
 - `end` - To force end the game

**Kunc**. Arguments: games (max number of rounds), points (number of ponts for winning), time (time to answer in seconds). Commands:

 - `g [pokemon]` - To guess the pokemon
 - `view` - To view the game status
 - `end` - To force end the game
 
**Rock, paper, scissors**. Single command game: `rps [rock/paper/scissors]`

**Ambush**. Arguments: roundtime (time per round). Commands:

 - `in` - To join the game. Use `out` to leave
 - `players` - To view the players list
 - `start` - To start the game
 - `fire [user]` - To kill other players
 - `end` - To force end the game

**Pass-The-Bomb**. Arguments: maxplayers (max number of players). Commands:

 - `in` - To join the game. Use `out` to leave
 - `players` - To view the players list
 - `start` - To start the game
 - `pass [user]` - To pass the bomb to another user
 - `end` - To force end the game

Youtube
------------

Commands for Youtube link recognition feature

 - `youtube [on/off]` - Enable / Disable YouTube link recognition

Auto-Invite
------------

Commands for auto-invite feature

  - `reloadroomauth [room]` - Reload roomauth if the autoinvite feature is not working well
  - `getroomauth [room]` - Upload roomauth to hastebin (dev command)

Group Chats
------------

Automated Promotion

 - `setautorank [on/off]` - Enable or disable automated promotion in a room
 - `autorank [rank/off]` - Set the autopromotion rank for all users when joining the room
 - `autorank [user], [rank/deauth]` - Set the autopromotion rank for a single user
 - `listautorank` - Upload the autopromotion list to Hastebin

Welcome private message. This can be spammable, much caution!

 - `wpm [enable / disable]` - Enable or disable this feature in a room. Only for excepted users.
 - `wpm view` - View the welcome private message set in a room
 - `setwpm [message]` - Set the welcome private message for a room
 - `delwpm` - Remove the welcome private message for a room

Developing commands for GroupChats feature

 - `ignoregroupchat [groupchat]` - temporarily ignore a groupchat (to leave a groupchat). Then you must edit the config to make it permanent
 - `unignoregroupchat [groupchat]` - unignore a groupchat
