# tele_bot_1
Primitive telegram bot to reply to Telegram messages with echo.

## Architecture

First, a few handler functions are defined. 
Then, those functions are passed to the Application and registered at their respective places.
Finally, the bot is started and runs until we press Ctrl-C on the command line.

## Usage

Basic Echobot example, 
Press Ctrl-C on the command line or send a signal to the process to stop the bot.