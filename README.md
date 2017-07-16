# goat-bot

A dumb Slack bot to make bad goat puns. Why did I even make this???

![](https://github.com/mazhang2718/goat-bot/blob/master/goatbot.png)

To execute, first retrieve a Slack bot token, and set it to environment variables, as described here: https://www.fullstackpython.com/blog/build-first-slack-bot-python.html

Then, run `python starterbot.py`, and you should be good (goat) to go!


The code is easily modifiable to run other text replacement auto-commands. To do so, add a line in the format of 
`if 'KEYWORD' in text` on line 43. 

Then, in the 'handle_command' function in `starterbot.py`, add a line in the format `command = command.replace('KEYWORD','REPLACEMENT-KEYWORD')`
