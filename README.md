AzerothCore Discord Bot to TrinityCore MASTER Discord Bot.


Bot startup
----------------------------

Info: This bot uses Discord ID and stores it into the SQL database auth => account => reg_mail

This way it verifies if the user is trying to use his own account created using the bot

Requirements:

    - NodeJS (Tested with v16.6.2)
    - Discord Account with a bot account for bot token

Installation:

    - Edit "config.js" and insert all your information: token, usernames, passwords, ...
    - Make sure your TrinityCore server has enabled SOAP.

Startup: 

    - Use a terminal
    - Command: npm start

Extra information:

    - Special thanks to Village#9461 (no github) for funding the project. (AzerothCore)
