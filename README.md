Command list
=============
`<>` denotes command arguments. `<??>` denotes optional command arguments

Mod-Only commands
-----------------
  * !setcooldown
    * Usage: `!setcooldown <command> <cooldown in secs>`
    * Sets the cooldown of the specified command to the specified duration
    * Example: `!setcooldown lurk 10` would set the cooldown of the `!lurk` command to 10 seconds
  * !resetraffle
    * Usage: `!resetraffle`
    * Purges all entries from the current raffle
  * !addcomm
    * Usage: `!addcomm <command> <output>`
    * Creates a new command for the bot
    * Example: `!addcomm example example text` creates a command `!example`, which prints `example text` to the chat
    * Example: `!addcomm example1 I am {u}` creates a command `!example2`, which prints `I am 'user'` where 'user' is the username of the user that typed the command
  * !setmodonly
    * Usage: `!setModOnly <command> <state(0 or 1)>`
    * Sets a command to be accessed only by moderators, or everyone
    * Example: `!setmodonly lurk 1` would give only moderators access to the `!lurk` command
    * Example: `!setmodonly lurk 0` would give everyone access to the `!lurk` command
  * !delcomm
    * Usage: `!delcomm <command>`
    * Deletes a command
    * Example `!delcomm lurk` would delete the `!lurk` command
  * !raffle
    * Usage: `!raffle <?numWinners?>`
    * Picks winner(s) from a raffle. Raffles don't reset after a winner is chosen, only the winner gets removed.
    * Example: `!raffle` would pick 1 winner from the current raffle
    * Example: `!raffle 5` would pick 5 winners from the current raffle
  * !permit
    * Usage: `!permit <username> <?time in sec?>`
    * Permits a non-sub to post links in chat for a specified amount of time.
    * Example: `!permit huddabegood` would permit 'huddabegood' to post links in chat for 30 seconds
    * Example: `!permit huddabegood 10` would permit 'huddabegood' to post links in chat for 10 secs
  * !so
    * Usage: `!so <channelname>`
    * Links to another streamers channel
    * Example: `!so huddabegood` would link to [twitch.tv/huddabegood](twitch.tv/huddabegood)
    * Example: `!so @huddabegood` would link to [twitch.tv/huddabegood](twitch.tv/huddabegood)
  * !rules
    * Usage: `!rules`
    * Prints the channel rules

General commands
----------------
  * !discord
    * Usage: `!discord`
    * Prints the invite link to Kotharion's discord
  * !followage
    * Usage: `!followage`
    * Prints how long the user has followed Kotharion
  * !muted
    * Usage: `!muted`
    * Reminds Kotharion that he is muted
  * !tophours
    * Usage: `!tophours <?top x?>`
    * Prints the users with the longest watch-time on Kotharion channel
    * Example `!tophours` would print the top 10 users with the longest watch-time
    * Example `!tophours 20` would print the top 20 users with the longest watch-time
  * !pickme
    * Usage: `!pickme`
    * Adds user to current raffle
  * !hug
    * Usage: `!hug <?what/who to hug?>`
    * User gives a hug
  * !quote
    * Usage: `!quote`
    * Prints a random quote from the quote-database
  * !lurk
    * Usage: `!lurk`
    * Indicates that the user is away from the stream
  * !uptime
    * Usage: `!uptime`
    * Prints how long Kotharion has been live
  * !addquote
    * Usage: `!addquote <quote>`
    * Adds a quote to the quote-database
    * Example: `!addquote That being said tho` would add the quote 'That being said tho' to the quote-database
  * !hours
    * Usage: `!hours`
    * Prints how many hours the user has been present during Kotharion's streams
  * !spoiler
    * Usage: `!spoiler`
    * Prints a message about spoilers
  * !commands
    * Usage: `!commands`
    * Prints a link to the commands available to everyone
  * !socials
    * Usage: `!socials`
    * Prints the link to all Kotharion's social media's
  * !emotes
    * Usage: `!emotes`
    * Prints all emotes available in Kotharion's chat
  * !boop
    * Usage: `!boop <?what/who to boop?>`
    * User boop's a snoot
  * !hype
    * Usage: `!hype`
    * Prints a bunch of emotes

Commands not in use
----------------
  * !rand
    * Usage: `!rand <min> <max>`
    * Prints a random number
    * Example: `!rand 0 100` would print a random number between '0' and '100'
  * !randsub
    * Usage: `!randsub <?number of subs to get?>`
    * Prints the username of a random subscriber
    * Example: `!randsub` would print the username of 1 random subscriber
    * Example: `!randsub 5` would print the username of 5 random subscribers
  * !randusr
    * Usage: `!randusr`
    * Prints the username of a random user from Kotharion's chat
