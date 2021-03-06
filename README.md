# Discord-Bot (MolemanBOT)
My own Discord bot built in Python using the discord.py API.

## THIS BOT IS OUTDATED AND HAS BEEN REPLACED WITH FLANDERSBOT
[View FlandersBOT HERE](https://github.com/MitchellAW/FlandersBOT)

[FlandersBOT](https://github.com/MitchellAW/FlandersBOT) is the better alternative and implements a much better use of the referencing system used by MolemanBOT, [FlandersBOT](https://github.com/MitchellAW/FlandersBOT) provides commands for The Simpsons and Futurama, just the same as this bot, but also offers support for Rick and Morty, 30 Rock and West Wing, in addition to the implementation of captions embedded in the screencaps.

MolemanBOT was originally designed to provide useful commands focused on The Simpsons. All API Calls that MolemanBOT makes
are performed with the requests module, blocking the bot from performing any other events until the API call completes, causing it to crash very often if any API call lasts a significant amount of time. This is why I am now considering this bot to be deprecated, as this is not the case with [FlandersBOT](https://github.com/MitchellAW/FlandersBOT).

MolemanBOT also features a join announcement feature over voice, when anyone joins/leaves the same voice channel as
MolemanBOT, the user's name will be announced over voice using Text to Speech (using gTTS), similar to what is provided in TeamSpeak by default.

# Requirements
Requires the following python modules to be installed:
Discord.py
Discord.py[voice]
ffmpeg (and added to PATH environment variables)
youtube_dl
requests
gTTS

## Commands
### !join

Will join the voice channel that you're in.

### !leave

Will leave the voice channel that the you're in.

### !play [youtube Url] or !play [song or video to search for]

Will begin playing the audio of the video/song provided.

### !pause

Will pause the current audio stream.

### !resume

Will resume the current audio stream.

### !stop

Will stop and end the audio stream.

### !invite

Will send a personal message with the invite link of the bot.

### !shutdown

Will make the bot logout and shutdown. Will only work for owner of the bot.

### !status [status here]

Will set the game playing status of the bot. Will only work for the owner of the bot.

### !joke

Posts a random Chuck Norris joke.

### !8ball

Will post a wise 8 Ball answer to any question.

### !coinflip

Will flip a coin and post the result.

### !roll [# of dice] D[# of sides] Example: !roll 3 D6

Will roll the dice specified and post the result.

### !slots

Will post a slot machine result.

### !cat

Will post a random cat picture or gif.

### !catfact (CURRENTLY OUT OF ORDER)

Will post a random cat fact.

### !catgif

Will post a random cat gif.

### !simpsons

Will post a random simpsons quote with the screen at the timestamp of the quote.

### !simpsonsquote [quote to search for]

Will search for the quote and post the subtitles and screen at the timestamp of the quote

### !simpsonsclip

Will post a random simpsons clip from the Simpsons Clip youtube channel.

### !boo

Will post a reply.

### !futurama

Will post a random futurama quote with the screen at the timestamp of the quote.

### !futuramaquote [quote to search for]

Will search for the quote and post the subtitles and screen at the timestamp of the quote

### !hots [hotslogs player ID] - Example: !hots 3141592

Will post the player's MMR for quick match and hero league

### !gwent [Card Name] - Example: !gwent Geralt

Will post the card description and picture of the gwent card. Has a max search length of 10 characters.
