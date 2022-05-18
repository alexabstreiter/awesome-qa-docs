# [AwesomeQA](https://home.awesomeqa.xyz) Docs

AwesomeQA takes away the burden of moderators by making the knowledge of your discord server accessible to anyone.
The discord bot moves your discord knowledge to Stackoverflow, generates FAQs and provides a framework for Q&A in Discord.

## Getting started
To setup the bot you need the `Administrator` permission or must be the server owner. If you don't have the `Administrator` permission, please contact the owner of the server and ask for this permission in order to set up the bot.

### Invite the Bot
You can invite the bot by clicking [here](https://discord.com/api/oauth2/authorize?client_id=955744627481255976&permissions=2147551360&scope=bot). Please give it all permissions, otherwise it may not function properly. 

## What the bot will do
It will go through the history of messages and cluster all questions and answers using state of the art NLP models.

Next, we will create statistics on your community's most frequent problems and curate FAQs for you.

You can [request your FAQs](mailto:ko.abstreiter@gmail.com) and question statistics once your bot is up and running.

Furthermore, the bot will optionally post the most important coding questions (asked at least 3 times) on Stack Overflow / Stack Exchange, so they are being indexed by Google. Please [contact us](mailto:ko.abstreiter@gmail.com) if you want to enable this feature.

## Commands reference
Coming soon:
- `/start`
    This command starts up the bot.
- `/stop`
    This command stops the bot, i.e. it will no longer read the messages or answer any questions.
- `/extract-faq <your-email>`
    Will send an email to the specific mail containing a predefined FAQ.
