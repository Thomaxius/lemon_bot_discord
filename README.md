# Developement continues here: https://github.com/thomaxius-and-co/lemon_bot_discord
# Developement continues here: https://github.com/thomaxius-and-co/lemon_bot_discord
# Developement continues here: https://github.com/thomaxius-and-co/lemon_bot_discord


#This is a (crappy) fork of lemon bot for discord: https://github.com/lemon65/lemon_bot_discord
	* Basically, what is done is that it has been ported to support Python 3.5 
	(Which is required by Discord.py v. 13). Not all features work, yet.




# Lemon Bot ![alt text](http://i.imgur.com/uhYjTMt.jpg "Lemon Bot Will Rule the World!")

## Features:
   * Youtube Integration
   * CleverBot Integration
   * Magic EightBall
   * Weather by ZipCode
   * Currency system
   * Black Desert Online scripts
   * WolframAlpha
   * Bing translate
   * Simple math
   * Casino:
	* Slot Machine
	* Blackjack

	
## Installation
   * Git clone the Repo. 
   	* git clone https://github.com/lemon65/lemon_bot_discord
  * Install dependencies with `pip install -r requirements.txt`
    * When you update dependencies, generate new requirements file using `pip freeze > requirements.txt`
  * Grab an API Key from, http://openweathermap.org
  * Also grab an API from https://www.wolframalpha.com/
  * You can then log into the bot manually and join a server or you can hack it to use the bot_join function.
  * Set the following environment variables:

    * OPEN_WEATHER_APPID
    * LEMONBOT_TOKEN
    * WOLFRAM_ALPHA_APPID
	* BING_CLIENTID
	* BING_SECRET
	
    To do this, you can either set them in system settings, or you can do SET
    valuename=value on windows command line before you run python.  Or you can
    hardcode them into run_lemon_bot.py

## Requirements:
   * Python 3.5.0
   * cleverbot 0.2.1 - https://pypi.python.org/pypi/cleverbot
   * bs4 - http://www.crummy.com/software/BeautifulSoup/bs4/doc/
   * Requests - http://docs.python-requests.org/en/master/
   * pickle - https://docs.python.org/2/library/pickle.html
   * discord.py - https://github.com/Rapptz/discord.py
   * bingtranslator https://github.com/wilfilho/BingTranslator
   * wolframalpha https://github.com/jaraco/wolframalpha
 
## Commands:
| Commands        | description |
| ------------- |:-------------:|
| !youtube [search_term]| Searches youtube for text that the user passes, then gives back a link to one of the videos. |
| !cleverbot [question] |  This will reach out to the cleverbot API and return an Answer. |
| !enchant [target_level][fail_stacks] |  this is a Black Desert command that figures out the enchanting chances for black stone upgrades. |
| !roll |  This rolls from 0-100, and returns the users name and the roll value. |
| !coin | Simple coin toss command, gives you a 50/50 chance. |
| !8ball [question] | This returns the eightball prediction and the question the user asked. |
| !spank [target_user] | This will return with a punishment for the target user. |
| !join [server join url] | Send the join URL to a sever where lemon bot is in and he will join the other server. |
| !weather [Zip Code] | This uses a Weather API to return weather information based on the zip code. |
| !slots | runs the slots, and uses the users money from the bank.|
| !clear | clears the chat log in that channel. |
| !bet [amount] | Set the users betting amount. |
| !reviewbet | Returns the users current bet. |
| !loan | Gives the user, a little cash, Max amount of $50 bucks. |
| !bank | Shows the user how much money they have. |
| !leader | Shows the Top five users with the most money. |
| !wa [query]| Searches WolframAlpha |
| !help | Returns the github page with Help information and commands. |
| !math | Does a calculation with a maximum of 3 digits |
| !blackjack | Play blackjack versus the dealer
| !translate <language>  <text> | Translate a text to the given language
| !clearbot | Deletes 50 of bot messages. Only available to admins.
| !pickone <arguments> | Picks a random choice out of X arguments
| !version | Displays the bot's version.

## Updates:
  * updates happen when I feel like it, if you see issues point them out and I will be happy to help.

## ToDo:
  * Google Search
  * Wiki Search
  * Other BDO scripts Etc. 
  * Music functions? 

  
  
## Help:
  * If you need help you can email me @ lemon65.twitch@gmail.com, or talk with me on my Team Speak
    (IP = ts.ramcommunity.com) user name is lemon65. 

## Notes:
  * I have seen lag issues with servers that can't parse the HTMl data quickly, for example a Raspberry-PI

## Thank you to:
  * Rapptz, for making discord.py - https://github.com/Rapptz/discord.py

## Copyright:

#################### Copyright (c) 2016 RamCommunity #################

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do so
