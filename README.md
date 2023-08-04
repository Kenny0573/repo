# Discord Bot Template

## Introduction
The Discord Bot Template is a powerful starting point for creating a feature-rich Discord bot, utilizing modern slash commands.  

Building commands for this bot is developer-friendly, as you only need to create a file in `SlashCommands/commands`, and the built-in script will take care of the rest.

**Features included in this template:**
- **ChatGPT**: This bot comes with a ChatGPT feature that can read chat history and remember users' Discord names, enhancing the interaction experience.
- **Music Player**: Enjoy music playback with the built-in music player, providing entertainment to users in your Discord server.
- **Tic Tac Toe**: A fun and classic game of Tic Tac Toe is included, adding a playful element to your bot.
- **Auto-generated Help Command**: Help users navigate your bot's commands effortlessly with the auto-generated help command.
- **Error Logging**: Keep track of any unexpected errors efficiently with the integrated error logging feature.

Start building your Discord bot with these powerful features using the Discord Bot Template!

# Deploy to [Zeabur](https://zeabur.com/)
You can quickly deploy your Discord bot on [Zeabur](https://zeabur.com/) using the following badge. Click on it to deploy!  

[![Deploy to Zeabur](https://zeabur.com/button.svg)](https://zeabur.com/templates/SKHTZA?referralCode=OnCloud125252)

If you choose to deploy your bot on Zeabur, you will get the basic features included in this template.  
> **Please note that if you want to customize the bot, add your own commands, or explore advanced features, it is recommended to follow the "Manually Install" section. This will give you full control over the bot and allow you to tailor it according to your specific needs.**

**Features included in this template:**
- **ChatGPT**: This bot comes with a ChatGPT feature that can read chat history and remember users' Discord names, enhancing the interaction experience.
- **Music Player**: Enjoy music playback with the built-in music player, providing entertainment to users in your Discord server.
- **Tic Tac Toe**: A fun and classic game of Tic Tac Toe is included, adding a playful element to your bot.
- **Auto-generated Help Command**: Help users navigate your bot's commands effortlessly with the auto-generated help command.
- **Error Logging**: Keep track of any unexpected errors efficiently with the integrated error logging feature.

# Manually install
## Requirements
- **Node.js** (version 16 or higher)
- **pnpm**  
    > **pnpm is the recommended package manager, but npm can still be used.**  
    > **You can install pnpm using `npm install -g pnpm`. For more installation option please visit [pnpm document](https://pnpm.io/installation).**

## Installation
1. Clone this repository
    ```bash
    git clone https://github.com/OnCloud125252/Discord-Bot-Template.git
    ```
2. Install dependencies
    ```bash
    pnpm install
    ```
    If you prefer to use `npm`, you can run `npm install` instead.
3. Set up `.env` file
    - Rename `.env-example` file in the project folder into `.env`.
    - Configure the following variables in `.env`:
        - **BOT_TOKEN**
        - **CLIENT_ID**
        - **MONGO_URI**
        - **OPEN_AI_KEY**
        - **ADMIN_USER_ID**
        - **HOST (Optional)**
        - **PORT (Optional)**
4. Run the bot
    You can use the following command to test the bot locally:
    ```bash
    npm start
    ```
    The terminal will output something like this if there aren't any error:  
    ![image](https://github.com/OnCloud125252/Discord-Bot-Template/assets/75195127/0745c434-97a4-4222-beda-22f654f9ec7d)

## For more details, please visit the [Wiki Page](https://github.com/OnCloud125252/Discord-Bot-Template/wiki/)
