This is study project that implements Telegram bot using spf13/cobra та gopkg.in/telebot.v3 frameworks.
My bot example: t.me/doDemo_bot

To use you may do following steps:
1. Install Go lang in yours workspace.
1. Clone this project from https://github.com/blyayshman/devops_first repo. 
    git clone https://github.com/blyayshman/devops_first
2. Create new telegram bot using BotFather:
    /new_bot
    enter name
    copy access token to clipboard
3. Update env variable TELE_TOKEN:
    read -s TELE_TOKEN
    insert from clipboard, <ENTER>
    export TELE_TOKEN
4. Run bot
    ./devops_first start
5. /start bot in Telegram client and try to send messages. All messages will echoed in telebot command line except "/start hello". This message couse telebot answer with message to telegram client. 

If you want to check telebot version you may use "version" parameter:
./devops_first version
Enjoy!


