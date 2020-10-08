# Adaptive Chat-bot

Chat Bot using Bot Framework 

## Prerequisites

- [Node.js](https://nodejs.org) version 10.14 or higher
- [Yarn pkg](https://yarnpkg.com/)


    ```bash
    # determine node version
    node --version
    # determine yarn version
    yarn --version 
    ```

## Installation

- Clone the repo using
    ```bash
        git clone https://github.com/rijan-chapagain/adaptive-chat-bot.git
    ```
    ```bash
    # Open folder that contains package.json
    cd adaptive-chat-bot
    ```

- Install modules

    ```bash
    yarn || npm install
    ```

- Start the bot

    ```bash
    yarn start || npm start
    ```

## Testing the bot using Bot Framework Emulator

[Bot Framework Emulator](https://github.com/microsoft/botframework-emulator) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the Bot Framework Emulator version 4.3.0 or greater from [here](https://github.com/Microsoft/BotFramework-Emulator/releases)

### Connect to the bot using Bot Framework Emulator

- Launch Bot Framework Emulator
- File -> Open Bot
- Enter a Bot URL of `http://localhost:3978/api/messages`
