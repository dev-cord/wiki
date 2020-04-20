Listed on this page are the various commands that GAwesomeBot contains, along with short descriptions of what those commands do. Click on a command name for detailed information on that command.

### How to Use Commands

Public commands are available in any channel/server where the bot is connected. The bot will respond when the message begins with his mention, for example: `@GAwesomeBot <command> <option1> <option2>`. This [can be changed](#prefix) per-server, however. You can always use `@GAwesomeBot help` to get the syntax for a specific server. For PM commands, simply start the message with the command name.

In the below guidance, square brackets (`[]`) indicate that a command parameter is optional. For example, `google <search> [<limit>]` would mean that `<search>` is a mandatory parameter, while the additional parameter `<limit>` is optional.

## General Commands

Each of the following are available for use in a public chat. Tag the bot and use one of these commands.

|Command|Description|
|--- |--- |
|[8ball](#8ball)|Predicts the answer to a question|
|[about](#about)|Tells you all about the bot and where to get more info|
|[afk](#afk)|Display AFK message for users when tagged|
|[alert](#alert)|Allows members to message the admins|
|[anime](#anime)|Searches anime shows using Hummingbird|
|[appstore](#appstore-and-linkme)|Searches the Apple App Store for one or more apps|
|[archive](#archive)|Produces a JSON file of the last _n_ messages in the channel|
|[avatar](#avatar)|Posts a user’s profile picture|
|[ban](#ban)|Removes a member from the server and prevents them from coming back|
|[calc](#calc)|Quickly evaluate a mathematical expression|
|[cat](#cat)|Random picture of a cat!|
|[catfact](#catfact)|Random fact about cats|
|[choose](#choose)|Randomly chooses from a set of options|
|[convert](#convert)|Converts between units of measurement and currencies|
|[cool](#cool)|Sets a command cooldown for the channel|
|[count](#count)|Keeps tallies of various things|
|[countdown](#countdown)|Set a timer for an event|
|[ddg](#ddg)|DuckDuckGo Instant Answers|
|[debug](#debug)|Provides system architecture information|
|[disable](#disable)|Disables one or more commands in a channel|
|[dog](#dog)|Random picture of a puppy!|
|[emotes](#emotes)|Shows the custom emojis on the server|
|[enable](#enable)|Enables one or more commands in a channel|
|[eval](#eval)|_Maintainer only:_ executes some JS code|
|[fortune](#fortune)|Tells your fortune (not really)|
|[games](#games)|Lists the games being played on this server in descending order|
|[gif](#gif)|Gets a GIF from Giphy with the given tags|
|[giveaway](#giveaway)|Easy way to randomly give away a secret of some sort|
|[google](#google)|Displays Google search and Knowledge Graph results|
|[help](#help)|Shows the complete list of bot commands and features specific to this server or help for a single command|[image](#image)|Searches Google Images with the given query and returns the first or a random result|
|[image](#image)|Searches Google Images with the given query and returns the first or a random result|
|[imdb](#imdb)|Provides movie and TV show data|
|[imgur](#imgur)|Uploads an image to Imgur|
|[info](#info)|Lists basic stats about this server|
|[join](#join)|Returns the OAuth URL to add the bot to a server|
|[joke](#joke)|Tells a random joke!|
|[kick](#kick)|Removes a member from the server|
|[linkme](#appstore-and-linkme)|Searches the Google Play Store for one or more apps|
|[list](#list)|In-chat to-do list|
|[lottery](#lottery)|Hourly GAwesomePoints lottery|
|[meme](#meme)|Generates a dank new meme|
|[messages](#messages)|Shows the number of messages a user has sent in the past week|
|[modlog](#modlog)|Moderation logging utility command|
|[mute](#mute)|Prevents users from sending messages in a channel|
|[nick](#nick)|Changes a member nicknames on the server|
|[nuke](#nuke)|Deletes number of messages in a channel, optionally only from specific user.|
|[numfact](#numfact)|Random fact about a number|
|[perms](#perms)|Modifies permissions for a role or user in a channel|
|[ping](#ping)|A useful command to tell if the bot is alive|
|[points](#points)|A quick way to get the number of points for a user|
|[pokedex](#pokedex)|Searches Pokemon species database|
|[poll](#poll)|Quick way to run a poll on a server|
|[prefix](#prefix)|Set command prefix|
|[profile](#profile)|An all-in-one command to view or set information about users|
|[quiet](#quiet)|Turns off the bot in the channel|
|[ranks](#ranks)|Lists the ranks of all members of the server|
|[reason](#reason)|Sets the reason for modlog entries|
|[reddit](#reddit)|Gets the top 1-5 HOT posts from a given sub on Reddit|
|[remindme](#remindme)|Set a reminder for yourself in a given number of days, hours, minutes, or seconds|
|[role](#role)|View or give yourself roles|
|[roleinfo](#roleinfo)|Gets information about roles|
|[roll](#roll)|Generate a random number. Without any parameters, this will roll a 6-sided die|
|[room](#room)|Allows anyone to create a temporary channel with a few other members|
|[rss](#rss)|Gets 1-5 entries from the provided RSS feed|
|[say](#say)|Says something in the chat|
|[shorten](#shorten)|Uses [goo.gl](http://goo.gl) to shorten or decode a URL|
|[softban](#softban)|Bans a from the server without deleting messages|
|[stats](#stats)|Shows the most active members, richest users, most played games, and most used commands on the server|
|[stock](#stock)|Fetches basic information about a stock symbol from Yahoo! Finance|
|[streamers](#streamers)|Shows live Twitch and YouTube Gaming streams|
|[strikes](#strikes)|Shows strikes for a user|
|[tag](#tag)|A quick snippet response system, inspired by the command in 42|
|[time](#tag)|Gets the time in a city or country|
|[translate](#translate)|Uses Microsoft Translate to translate a word/phrase into another language|
|[trivia](#trivia)|AwesomeTrivia, a fun question-and-answer group quiz game|
|[twitter](#twitter)|Fetches the Twitter timeline for a given user and shows the last 1-5 tweets|
|[unban](#unban)|Unbans a user|
|[unmute](#unmute)|Allows a muted user to speak in the channel|
|[urban](#urban)|Defines the given word from Urban Dictionary|
|[warn](#warn)|Add a modlog entry (if enabled)|
|[weather](#weather)|Gets the current weather and forecast for the given location from MSN Weather|
|[wiki](#wiki)|Shows the first three paragraphs of the Wikipedia article matching the given search query|
|[wolfram](#wolfram)|Displays an entire Wolfram\|Alpha knowledge page about a given topic or person|
|[xkcd](#xkcd)|Fetches today’s XKCD comic or by ID|
|[year](#year)|Displays the exact amount of time until next year!|
|[youtube](#youtube)|Gets a YouTube link with the given query, including channels, videos, and playlists|

Anything else will be passed to the active chatterbot [Program O](http://www.program-o.com/).

### 8ball

**Usage:** `8ball` followed by a question

The 8-Ball was a toy that would give you a preset answer after you asked it a question and shook the toy. This command emulates that toy. Giving you one answer out of the selection of preset responses, use it to predict your future or make potentially life-changing decisions. The 8-Ball is never wrong.

### about

**Usage:** `about`

The about command tells you about the bot and where to find additional information. It does not take any parameters or options. In the official GAwesomeBot, it returns the following:

![about message](https://s24.postimg.org/v3ucv0qn9/gabout.png)

### afk

**Usage:** `afk <message>` or `afk .` to remove AFK message.

This command allows users to set an AFK message that will be displayed by the bot whenever the user is tagged in a channel. It does not take any parameters or options.

### alert

**Usage:** `alert <message>`

Allows users to message bot admins. The bot will PM all bot admins with the message, along with the username of the sender and the name of the channel from where it was sent.

### ~~anime~~

**Usage:** `anime <search query> [<limit>]`

~~This command allows you to quickly look up information on a certain anime from [Hummingbird](https://hummingbird.me/).~~
Not currently working (see [here](https://github.com/GilbertGobbels/GAwesomeBot/issues/20)), as the Hummingbird API has been closed.

### appstore and linkme

**Usage:** `appstore app1[,app2,...]` or `linkme app1[,app2,...]`

Have you ever wanted to quickly link a cool app for someone? This command lets you do just that. It doesn’t even require tagging the bot; regardless of platform, you can easily search for app listings and pull up their ratings and prices. For the Google Play store, use `linkme`; for the Apple App Store, use `appstore`. The syntax is the same for both commands, but we will use linkme for examples here.

To fetch an app link, send a message with `linkme <app name>` and the bot will send a listing with the name, developer, rating, price, and URL. You can fetch multiple apps by using `linkme app1, app2, app3`. Some apps are restricted by region, but GAwesomeBot searches the US store by default.

### archive

**Usage:** `archive <number of messages>`

Produces a JSON file of the last _n_ messages in the channel, uploaded as an attachment.

### avatar

**Usage:** `avatar <username>`

Wanted to see someone’s avatar, but didn’t want the spam that comes with `profile`? Well this one’s for you. Simply say `avatar` followed by the username of the person whose avatar you want to see. It’s that’s easy.

### ban

**Usage:** `ban <username>[|<reason>]`

Bans the username specified in the command and deletes the user's messages, recording a given reason if provided. If you do not wish to delete the user's messages, use [softban](#softban).

### calc

**Usage:** `calc <expression>`

Returns the outcome of a mathematical expression. e.g. `calc (3*4)+6` would return `18`.

### cat

**Usage:** `cat`

Would you like a random picture of a cat? Of course you would, which is why this command exists. If you’re lucky you might even get a gif.

### catfact

**Usage:** `catfact`

Entertain your server with more facts about cats than you ever imagined!

### choose

**Usage:** `choose option1|option2|...`

Sometimes you have a tough decision to make, and the best way out is to seek GAwesomeBot’s wisdom - use the choose command. Provide 2 or more options, separated by `|`, and GAwesomeBot will randomly pick one.

### convert

**Usage:** `convert <numerical quantity> <original unit> to <desired unit>`

This command converts between units of measurement and currencies. Here’s a list of supported units:

*   Length
    *   mm
    *   cm
    *   m
    *   in
    *   ft
    *   mi
*   Mass
    *   mcg
    *   mg
    *   g
    *   kg
    *   oz
    *   lb
*   Volume
    *   mm3
    *   cm3
    *   ml
    *   ltr
    *   m3
    *   km3
    *   tsp
    *   tbsp
    *   in3
    *   fl-oz
    *   cup
    *   pnt
    *   qt
    *   gal
    *   ft3
    *   yd3

You can also use standard currency codes, with data provided by [Open Exchange Rates](https://openexchangerates.org/), or `F` or `C` for temperature conversions.

### cool

**Usage:** `cool <cooldown length>|<cooldown duration>` or `cool .` to end cooldown

Sets a cooldown for users running bot commands in the channel. Time can be specified in milliseconds (i.e. 60000 = 1 minute), or in normal language (e.g. `1 minute`).

### count

**Usage:** `count <name>[|"." or "+1" or "-1"]`

Keeps a count of various things across a server. To create a count use `count <name>`. GAwesomeBot will respond `I can't find a count called <name>. Would you like to create it?` Reply with `Y`. For existing items use `count <name>|+1` or `-1` to increase their count. The value of an existing count can then be viewed using `count <name>`. Run `count <name>|.` to remove a count.

### countdown

**Usage:** `[<event>][|<time from now>]`

Starts a timer for a particular event in a channel. Time can be specified in milliseconds (i.e. 60000 = 1 minute), or in normal language (e.g. `countdown Turn off the oven|35 minutes`). Use without any parameters to display any unexpired countdowns running in the channel.

### ddg

**Usage:** `ddg <query>`

Searches DuckDuckGo Instant Answers for the answer to a question.

### debug

**Usage:** `debug`

The debug command provides system archictecture and memory usage information. It does not take any parameters or options. In the official GAwesomeBot, it returns something like the following:

![debug message](https://s28.postimg.org/lxgwdeyzh/gdebug.png)

### disable

**Usage:** `disable <command> <command>...`

Disables one or more commands in a channel. Use [enable](#enable) to re-enable commands in a channel.

### dog

**Usage:** `dog`

Tired of seeing random pictures of cats? From the team that brought you `cat` comes a command like no other: `dog`. Produces a random picture of a dog.

### emotes

**Usage:** `emotes`

Shows the custom emojis available on the server.

### enable

**Usage:** `enable <command> <command>...`

Enables one or more commands in a channel, that have been [disabled](#disable).

### eval

**Usage:** `eval <code>`

_If you are a bot maintainer_, you can use this command to run some JS code for testing purposes. This is useful for live debugging.

### fortune

**Usage:** `fortune`

Have you ever wondered what the future had in store for you? Now there's a way to find out (or maybe not). From the team that brought you `cat` and `dog` comes a new command that is truly ahead of its time. Run `fortune` and the bot will use its mystic powers to determine your fate. 

### games

**Usage:** `games`

Lists all of the games played on the server in the last week, in descending order of the cumulative number of hours played.

### gif

**Usage:** `gif <query>`

Fetches a GIF from Giphy with the given tags. There isn’t anything else to it; just use `gif <query>` and let the memes flow…

### giveaway

**Usage:** `giveaway`

Enter an existing [giveaway](#giveaway-pm) that is running in a channel.

### google

**Usage:** `google <query> [<limit>]`

Have you ever been too lazy to switch out of Discord and Google something? This command displays Google search and Knowledge Graph results for a given search query. Use `<limit>` to specify the number of hits to return (1-5), or exclude it to use the default of 1.

### help

**Usage:** `help` or `help <command name>`

This command provides information about bot commands. With no options, the user will receive a PM containing a complete list of commands and features specific to the server, which they have permission to run. If including a command name as a parameter, extended help for that command will be displayed in the channel.

### image

**Usage:** `image <query> [random]`

Much like the GIF command, the image command simply fetches the top Google Image Search result for a given query. Using the `random` option at the end will make it a random hit instead of top (for example: `image GAwesomeBot random`).

### imdb

**Usage:** `imdb <query>`

Searches [IMDb](https://www.imdb.com) for your search query and returns the most relevant result.

### imgur

**Usage:** `imgur` followed by a URL to an image.

Quick and simple command to upload an image to Imgur and give you a hotlink to it.

### info

**Usage:** `info`

Displays basic information on your server, such as the number of members and the server owner.

### join

**Usage:** `join`

With the Discord API, bots cannot accept normal invites to servers. Instead, you can use this command (it does not take any parameters) to get the OAuth URL for the bot, which will allow you to add it one of your servers. Note that you must have the Manage Server permission in a server to add a bot to it.

### joke

**Usage:** `joke`

This one is dead simple. Use the command and it will tell you a random joke!

### kick

**Usage:** `kick <username>[|<reason>]`

Much like the [ban](#ban) command, this command will kick the specified username, with a given reason if provided.

### list

**Usage:** `list <new item>` or `list <item no>|done`, `list <item no>|.` or `list <item no>|<content>`

An in-chat to-do list for your server. New entries are added with the first command, and entries can be marked complete, deleted or replaced with `done`, `.` and `<content>` respectively. Simply typing `list` will display the entire to-do list.

### lottery

**Usage:** `lottery start` or `lottery enroll` or `lottery .`

Runs an hourly AwesomePoints lottery. `start` begins a lottery in a channel. Users can then `enroll` in the lottery. After 1 hour, or when `.` is triggered, the lottery will end and a winner (who has enrolled) will be chosen and awarded a small amount of AwesomePoints. If the command is run without any options (`lottery`), the status of any lottery in the given channel will be displayed.

### meme

**Usage:** `search <query> or [<meme key>|]<top>[|<bottom>]`

Dank memes are loved by many, but there’s never enough for everyone. With GAwesomeBot, you can create new memes using the `meme` command. Provide the name of the meme image, top text, and bottom text as parameters separated by `|`. For example, you could use `meme one doesn't simply|one does not simply|defeat gawesomebot`:

![gawesomebot meme](https://s27.postimg.org/7d2m8kazn/meme.jpg)

You can also use `search <query>` to search for meme keys.

### messages

**Usage:** `messages [<user or "me">]`

This command is much like the [points](#points) command, providing a simple way to check the number of messages you or another user have sent on the server in the past week. Use without a parameter to view the list for the entire server, use the `me` option to check for yourself, or provide a username as the parameter.

### modlog

**Usage:** `"enable" <channel> or "disable" or "remove" <case ID>`

GAwesomeBot's moderation logging feature makes it easy for moderators to keep track of why members have been muted, kicked, and banned. It is integrated with other GAwesomeBot moderation commands: `ban`, `kick`, `mute`, `reason`, `softban`, `unban`, `unmute`, `warn`. Moderation logging works as a full replacement for kick/ban status messages, and stores incidents as cases with reasons for each action. Whenever an incident occurs, the bot will post a message in channel where moderation logging has been enabled.

![modlog-example](https://s27.postimg.org/gkknpu7vn/modlogex.png)

Moderation logging may be enabled/disabled from within the admin console under *Management* -> *Moderation*.
![modlog-enable](https://s23.postimg.org/uqiuh84mz/modlogen.png)

Alternatively, the above could be accomplished by a bot admin using the `modlog` command (`modlog enable #testing`), without having to log in to the bot's admin console. Likewise, moderation logging may be disabled by running `modlog disable`. Individual infractions may be removed from the moderation log by running `modlog remove <case ID>`.

### mute

**Usage:** `mute <username>[|<reason>]`

This command will mute the specified user in a particular channel (with a given reason if provided), removing the user's permission to send messages in that channel.

### nick

**Usage:** `nick [<user>|<name>]` or `nick <name>`

This command allows bot admins to change other user's nicknames on a server, by running `nick @user|newnick`. It may also be used by a bot admin to change their own nickname on a server (note that this will not work if you are the server owner). Run without any options, this command will display a bot admin's nickname on a server.

### nuke

**Usage:** `nuke <search limit> [<content>` or `":"<query>` or `">"<message ID>` or `"<"<message ID>` or `<user>]`

Deletes messages in a channel, all or from a user. The last *x* number of messages may be deleted with `nuke <search limit>`. Alternatively, it is possible to remove the last *x* number of messages containing a word or string: for example, after a series of users spamming the word "noob" in a channel, a bot admin could run `nuke 50 noob` to search the last 50 messages in the channel for messages "noob" and delete only those messages. It is also possible to delete all messages within the search limit *except* those matching `:<query>`. Another option is to delete all messages from a particular user i.e. `nuke 50 @username`.

The final option is to delete a number of messages before or after a *specific* message, by providing the ID of that message. To allow you to get a message's ID, go to Discord settings -> Appearance and tick *Developer Mode*.

![copy-msgid](https://s30.postimg.org/rj03k6fq9/2017_01_25_17_19_44.gif)

Imagine there were a spam attack in a channel, followed by users continuing an on-topic conversation. Simply purging the last *x* messages would also purge a relevant discussion. Instead, we can find the message ID of the last genuine message before the spam attack. If the ID of the above message (copied to clipboard) is '273859885995917313', we can delete the next 20 messages after that message with `nuke 20 >273859885995917313`.

### numfact

**Usage:** `numfact <number>`

Use this command to get an interesting (if a little useless) fact on the number you chose. Did you know that a haiku has 17 syllables in it? Well now you do! Numbers must be in arabic numeral form.

### perms

**Usage:** `perms [<user or role>][|<permission name>]`

View and add permissions for a role or user in a channel. Run without any options (`perms`) to get a list of permissions names. Run `perms <user or role>` to see the permissions that user/role has in the channel. Run `perms <user or role>|<permission name` to add the permission to the user, or to remove the permission if already added.

### ping

The simplest command of them all! Ping gives you basic runtime stats for the bot: version, uptime, number of servers/users, and, if available, the status page URL. This command is also really useful for checking if the bot is alive.

![ping command](https://s30.postimg.org/n14ge2edd/pong.png)

### points

**Usage:** `points [<user> or "me"]`

The points command provides a minimal way to check how many points a user has or get a list of all the members with positive points on the server. `points me` gets your points, `points <username>`, and just `points` lists users’ points on the server in descending order.

We’ll also take this opportunity to describe the GAwesomePoints karma system. This is one of GAwesomeBot’s exclusive features, and it’s integrated throughout the bot. It works much like karma on Reddit, but can be disabled per-server and there’s no downvoting. Use `@user +1`, `@user ^`, `@user up`, `^` (for the previous message) to upvote a user. This will give them 1 point without taking any away from you. `@user gild`, on the other hand, will give the user 10 points from your points. On servers with spam/NSFW filter enabled, you’ll _lose_ 50-100 points for violations. If the server has stats enabled, you’ll get points proportional to your activity level if you are one of the 5 most active on the server at the end of the week.

### pokedex

**Usage:** `pokedex [<species>]`

Searches Pokemon species database and returns key information on the species.

### poll

**Usage:** `poll [<no. of option>]`

The [poll PM command](#poll-pm) is used to create live, in-chat polls. This public poll command (used in channel) allows users to vote in an existing poll (`poll <no. of option>`), or to run simply `poll` to see the status of any ongoing poll in the channel.

### prefix

**Usage:** `prefix [<new command prefix>]`

GAwesomeBot's default command prefix is set to `@mention`, so to use a command (e.g. ping) we would mention GAwesomeBot followed by the command (e.g. `@GAwesomeBot ping`). By changing the prefix to `&`, for example, we would then be able to type the message `&ping` to trigger the same command.  The command prefix may be changed from within the admin console under *Commands* -> *Command Options*.

![prefix](https://s28.postimg.org/w59hjt7b1/prefix.png)

This is more easily accomplished by a bot admin using the prefix command, without having to log in to the bot’s admin console. Simply run `prefix <new command prefix>` to change the command prefix. Running `prefix` by itself will display the existing command prefix (but in order to do this you would need to know the prefix in the first place!)

### profile

**Usage:** `profile [<username>]`

This is the all-in-one command to view information about users. If no parameters are provided, it will show your user profile. This includes ID, avatar URL, status, age of discord account, points, strikes, rank, roles, the time you joined the server, time last seen, and any custom information you have set. If the parameter is a username, that user’s profile will be displayed.

### quiet

**Usage:** `quiet ["all" or <time>]`

This command allows bot admins to turn the bot off the in the current channel, or all channels with the `all` option. Alternatively, specify a period of time (either milliseconds [1 minute = 60000] or normal language) as the parameter to turn the bot off for that amount of time. You can turn the bot back on at any time with the `start` or `start all` commands.

### ranks

**Usage:** `ranks [<user or rank>]`

This command lists the ranks of all members on the server. With the option `<user>`, the command displays the rank of that user. Alternatively, you may specify a rank to see all members on the server with that rank.

### reason

**Usage:** `reason <case ID><reason>`

This command works with the [moderation log](#modlog) to set the reason for a particular admin action (e.g. warn, kick, ban, etc), to change the reason or to add a reason if one was not specified in the initial command.

### reddit

**Usage:** `reddit [<subreddit>] [<limit>]`

Fetches the _n_ HOT posts from a given subreddit. If `limit` is not provided or is not within 1 and 5, _n_ defaults to 1. When providing the subreddit, exclude `/r/` from the name. The response will include the score, title, time, poster, no. of comments, and link for each result. Without any options, this command will display reddit's top 3 HOT submissions.

### remindme

**Usage:** `remindme <time from now>|<reminder>` or `remindme to <reminder> in <time from now>`

Sets a reminder to do something in a given amount of time. You’ll get the reminder via PM. Reminders are persistent across bot restarts. `<time from now>` should consist of a number followed by the duration of time (e.g. `3 days`). Supports `seconds`, `minutes`, `hours`, `days` `weeks`, `months` and `years` (or `s`, `m`, `h`, `d`, `w`, `y` for convenience) e.g. `3d` is the same as `3 days`.

![remindme-example](https://s30.postimg.org/fmx7k4mg1/reminder.png)

### role

**Usage:** `role [<name>][|"." or <hex color> or "hoist" or <user> or <name>]`

By default `role` will display a list of your roles on the server. If you have role selection enabled on your server, you can use this command to add yourself to a role (or remove yourself from a role if you are already a member of that role) by typing `role <name>` . You can add other users to roles with `role <name>|<user>`. Use `role <name>|.` to delete a role (you will be asked if you are sure; reply with `y` to confirm). Change the colour of role with `role <name>|<hex color code>` (see a list of hex colours [here](http://htmlcolorcodes.com/)). Finally, you may also use `role <name>|hoist` to make a role appear separately on the user list (or run the command again to unhoist it).

### roleinfo

**Usage:** `roleinfo [<role>]`

By default `roleinfo` will display a list of all the roles on the server and all the members of each role. If you specify a role name, the bot will display the role's ID, hex colour, age, number of members, and its permissions.

### roll

**Usage:** `roll [<minimum number inclusive>] [<maximum number inclusive>]`

The roll command generates a random number. Without any parameters, it will roll a 6-sided die. With one parameter, a number between 1 and `<number>` (inclusive) will be rolled. Otherwise, include a minimum integer and maximum integer as the range for the random number.

### room

**Usage:** `room "text" or "voice" [<user 1>][|<user 2>]`

The room command creates a temporary text or voice channel for a small number of members to use. Using `text` creates a text channel while `voice` creates a voice channel. Specifying users (usernames separated by `|`) grants permissions to those users to access the temporary channel.

If you have created a text channel with this command, you may run `room` in that channel and you will be prompted to delete the channel or to add new members, using `y` and `n` to indicate yes or no answers to questions.

### rss

**Usage:** `rss <feed name or URL> [<limit>]`

Gets the top _n_ articles from an RSS feed. Feed names are registered per-server, with the one default being `gnews` for Google News. Bot admins may have added additional RSS feeds in the server (under *Commands* -> *Command List* -> *RSS Feeds* in the admin panel); you can view these by running the rss command on its own. You can also provide a full RSS feed URL for other feeds. The `limit` is a value between 1-5 and defaults to 3 if it is not provided. The response for this command will include the title of each RSS article.

### say

**Usage:** `say <what you want the bot to say>`

The say command makes the bot say something. This might seem useless, but if you delete the message with your command afterwards, it can give the impression that the bot is sentient ;)

### shorten

**Usage:** `shorten <URL>`

Quickly shorten URLs with this command. It’s pretty simple: provide a full URL as the parameter to get a shortened [goo.gl](https://goo.gl) link, or provide a [goo.gl](http://goo.gl) URL to get the full target link.

### softban

**Usage:** `softban <username>[|<reason>]`

Bans the username specified in the command, with a given reason if provided. Unlike [ban](#ban), `softban` does not delete the user's messages.

### stats

**Usage:** `stats ["clear"]`

The stats command is the frontend for GAwesomeBot’s comprehensive stats system. It shows the most active members, richest members (by points), most played games, and bot command usage on the server. If you are a bot admin, you can use the `clear` option to reset stats.

### stock

**Usage:** `stock <symbol>`

Fetches information about a given stock symbol from Yahoo! Finance. That’s pretty much it.

### streamers

**Usage:** `streamers`

This command find any users currently streaming on Twitch or YouTube and displays links to their streams.

### strikes

**Usage:** `strikes [<user>]`

Use this command to view a list of users on your server who have strikes, or see detailed information on a user’s strikes if the `<user>` option is provided.

### tag

**Usage:** `<tag name>|["." or <content>]`

Inspired by the tag command in the 42 bot, this command provides access to a database of custom tags. To set a tag, use, for example, `tag Bob|...the Builder!`. This will make the bot return `...the Builder!` whenever you use `tag Bob`. You can use `tag Bob|.` remove the value for this tag. There are a few built-in tags: `shrug`, `lenny`, some copypastas, and the name of any Twitch emote. Bot admins can delete all tags on the server with `tag clear`. You can view all tags by using the command without any parameters.

### time

**Usage:** `time <location> or <user>`

Members of the Discord community are located all around the world, in different timezones. Use this command to check the time in a certain city or country. If you don't provide a location, the command will default to the location saved in your [profile](#profile-pm); if you haven't set a location the bot will prompt you to do so. You may also check the time in another user's location, if they have set a location in their profile, by running `time @username`.

### translate

**Usage:** `translate <text> <source lang> to <target lang>`

Discord is a global service, with users speaking a variety of languages. This command allows you to easily translate a word or phrase from a given language to your native tongue. For example, `translate Gracias ES to EN` will return `Thank you`. You must use [language codes](https://www.sitepoint.com/web-foundations/iso-2-letter-language-codes/) (e.g. EN, ES, etc.) instead of the full language name.

### trivia

**Usage:** `trivia <start, end, next, or answer> [<question set to use>]`

One of GAwesomeBot’s best features is its fun, built-in group trivia game. You can start a game in a public channel with `trivia start` (to use the default set) or `trivia start <question set name>` (to use a custom set; a list of custom sets is available in the help command). Once started, you can use `trivia next` to skip `trivia <answer>` to provide a response. Your answer doesn’t have to match the real answer exactly, but should be within a few characters’ difference. You’ll be awarded 5 points for each correct answer. Once you’re done, use `trivia end` to view your group score.

### twitter

**Usage:** `twitter <username> [<limit>]`

The Twitter command fetches a Twitter user’s timeline. By default, 3 tweets are returned, but you can include the `limit` parameter set a value between 1 and 5.

### unban

**Usage:** `unban <user>[|<reason>]`

Unbans the username specified in the command, recording a given reason if provided.

### unmute

**Usage:** `unmute <user>[|<reason>]`

Allows a muted user to speak in the channel, recording a given reason if provided.

### urban

**Usage:** `urban <query>`

If you’ve ever wanted to quickly grab a definition, this command is for you! It shows the community-sourced definition of the given word/phrase and its score.

![urban command example](https://s30.postimg.org/yfn32ssxt/urban.png)

### warn

**Usage:** `warn <user>[|<reason>]`

Issues a strike against the username specified in the command, recording a given reason if provided. This will be added to the modlog, as well as the user's bot profile (viewable with the `profile` or `strikes` commands). The user will receive a PM notifying them that they have received a strike, and the reason why (if provided).

Tip: strikes can be removed from within the admin console under *Management* -> *Moderation* -> *Strikes*.

### weather

**Usage:** `weather <location> [<unit>]`

Use this command to check the current weather in a certain city or country, together with a forecast for tomorrow. If you don't provide a location, the command will default to the location saved in your [profile](#profile-pm); if you haven't set a location the bot will prompt you to do so. The `unit` defaults to celsius (C), but F may be specified for results in fahrenheit.

### wiki

**Usage:** `wiki <query>`

Well, this is pretty simple: this command fetches the first 3 paragraphs of a Wikipedia article. Make your query as specific as possible.

### wolfram

**Usage:** `wolfram <query>`

For more detailed information than a Wikipedia article, you can use the wolfram command to get the full Wolfram|Alpha result for a query. This includes all sections and images.

### xkcd

**Usage:** `xkcd [<comic ID>]`

Fetches today's [XKCD](http://xkcd.com) comic, or a specific comic if an ID is specified.

### year

Displays the remaining time until next year, in days, hours, minutes and seconds.

### youtube

**Usage:** `youtube <query> [<limit>]`

This command searches YouTube with the provided query and returns _n_ results, which could be videos, playlists, or channels. Discord will allow you to play videos inline. If `limit` is not provided or is not within 1 and 5, _n_ defaults to 1.

## NSFW Commands

Each of the following NSFW commands are available for use in a public chat. Tag the bot and use one of these commands.

|Command|Description|
|--- |--- |
|e621|Searches by tag on [e621.net](http://e621.net)|
|rule34|Searches by tag on [rule34.xxx](http://rule34.xxx)|
|safebooru|Searches by tag on [safebooru.org](http://safebooru.org)|

### e621/rule34/safebooru

**Usage:** `<query> [<limit>]`

Searches by tag on the particular website. The optional limit parameter limits the number of returned results to a given number.

## PM Commands

The following commands work via PMing the bot on Discord. Tagging the bot is not necessary, nor is using a command prefix.

|Command|Description|
|--- |--- |
|[afk](#afk-pm)|Sets a global AFK message to be shown when you are tagged|
|[config](#config)|Provides a link to the online settings page for a server or the bot in general|
|[giveaway](#giveaway-pm)|Starts a giveaway to give something away in a channel|
|[help](#help-pm)|Displays a list of available PM commands|
|[join](#join)|Provides a Discord link for a user to join the bot to their server|
|[poll](#poll-pm)|Starts a new poll in the main chat|
|[profile](#profile-pm)|Adds a value in your user profile|
|[reload](#reload)|Allows a bot maintainer to reload a command from file (after modification)|
|[remindme](#remindme-pm)|Set a reminder for yourself in a given number of days, hours, minutes, or seconds|
|[say](#say-pm)|Says something in the main chat|
|[servernick](#servernick)|Set an alias in your profile for a particular server|

### afk (PM)

**Usage:** `afk <message>`

Sometimes you know you’re going to be away from keyboard (AFK) for some time and want to let others know if they tag you. With GAwesomeBot, you can use the `afk` command to set a message (e.g. `afk doing the dishes`) via PM and when someone tags you in any server where the bot is present, they’ll get: `@you is AFK: doing the dishes`. When you’re back, use `afk .` to remove the message or just send a message in any server (and the AFK message will be auto-removed).

Tip: this is the same as the public `afk` command, except that it is global and works across all servers where the bot is present.

### config

**Usage:** `config [<server name>]`

This is a legacy command, that gives you a link to the admin/maintainer console. This command is no longer needed, as logins to the bot's web console are handled directly in the browser, using your Discord account to authorize access.

### giveaway (PM)

**Usage:** `giveaway [<server name>]|#<channel>`

This command allows you to give something away in a channel. Simply PM the bot to start a giveaway, and you will be asked to provide secret information (such as a game key), a title for the giveaway, and to specify the amount of time it should last (in milliseconds [1 hour = `3600000`]). The giveaway will be announced in the channel and users may then enter using the [public giveaway command](#giveaway). Once the giveaway ends (when the time expires, or if you manually end it by PMing the bot the same command and responding `y`) the bot will select a random user from the entrants and PM them the secret information you provided earlier.

### help (PM)

**Usage:** `help`

PMs you the commands and usage instructions for all available PM commands on the bot.

### poll (PM)

**Usage:** `poll <server name>|#<channel name>`

Another one of GAwesomeBot’s best features is its ability to conduct live, in-chat polls; this command is the way to start one. Providing the bot admins in the server have enabled the poll option, you can provide the server name and channel name as parameters to get started with creating a poll. You will be prompted for the title of the poll and the options. You can use the default yes/no option by responding with `.` or make your own, separated by commas.

If you are the poll creator, you can end the poll by PMing the bot `poll <server name>|#<channel name>` again - the bot will ask if you would like to end the poll and see the results; type `y`.

Once the poll has been started, users may vote in the channel in which it was created using the [poll](#poll) command, _or_ discreetly via PM (by PMing the bot `poll <server name>|#<channel name>`; if a user is not the poll author, this will prompt them to vote in the poll).

**Tip**: instead of having to type the name of a server for `<server name`, you can use the [servernick](#servernick) command to set up an alias for a server. e.g. instead of having to type `poll /r/Watch_Dogs|#main-chat`, you could use `poll wd|#main-chat` ('wd' being an alias for a server called '/r/Watch_Dogs').

### profile (PM)

**Usage:** `profile ["setup" or <field>][|"." or <value>]`

The profile PM command is how you add information to your [user profile](#profile). Use `profile <field>|<value>` to set a field to a value. Use `profile setup` to set up your initial profile.

### reload

**Usage:** `reload "pm" or "public"/<command>`

This command is for bot maintainers only. Allows a bot maintainer to reload a particular command from file. This could be useful if a command's source code has been updated but the maintainer does not wish to restart the bot.

### remindme (PM)

**Usage:** `remindme <time from now>|<reminder>` or `remindme to <reminder> in <time from now>`

This command is the same as the [public remindme command](#remindme) but is global, and works via PM rather than in a channel.

### say (PM)

**Usage:** `say <server name>|#<channel name>`

This command is an admin-only version of the [public say command](#say), useful for reminding members of the rules. Provide the server name and channel name and the bot will respond, asking what you want the bot to say in the channel (you can use the usual Discord markdown syntax for this). The bot will speak in the main chat and other members will not be able to tell who sent the message.

### servernick

**Usage:** `servernick [<nick>][|<server>]`

This command allows you to set an alias for a server, so you don't have to type the full server name when running certain PM commands (e.g. `say` above). For example, instead of having to type `say /r/Watch_Dogs|#main-chat`, you could use `servernick wd|/r/Watch_Dogs` to set up an alias 'wd' for a server called '/r/Watch_Dogs', and in future could type `say wd|#main-chat`.
