# Active Developer Badge Discord Bot

# Requirements ✅
- [NodeJS](https://nodejs.org/en) LTS release
- A Discord Bot (create one using the [Discord developer portal](https://discord.com/developers/applications))
- A Discord server that you own.
    - "Enable Community" should be completed, or this won't work.


# Basic Usage
### 🟢 <ins>Step 1</ins>
Make sure that LTS [Node.JS](https://nodejs.org/en) is installed on your computer.
### 🟢 <ins>Step 2</ins>
Extract this repo and open a command line in the folder
### 🟢 <ins>Step 3</ins>
Open CMD/Terminal inside this folder, run `npm install` to get required dependancies
### 🟢 <ins>Step 4</ins>
Create a new Discord server and be sure to enable community features or else this whole process won't work.
### 🟢 <ins>Step 5</ins>
Create a new Application in [Discord's Developer Portal](https://discord.com/developers/) and enable the bot in the tabs to the left.
### 🔴 <ins>Step 6</ins>

Create `config.json` into the this folder and insert your the **token of your application**, **application ID**, and the **guild ID**
- Should look something like this
    ```json
    {
        "token":"<TOKEN>",
        "clientId": "<CLIENTID>",
        "guildId": "<GUILDID>"
    }
    ```
    - Find the token of your App in the [Discord Developers' Portal](https://discord.com/developers/)
        - You may need to regenerate to copy it
    - You can find the application ID also in the [Discord Developers' Portal](https://discord.com/developers/)
    - Provided you have developer mode enabled on the Discord client, you can right click the server icon on the left and copy the guild ID.
        - Settings > Advanced > Developer Options
### 🟢 <ins>Step 7</ins>
Open CMD/Terminal inside this folder run `node deploy-commands.js` then run `node index.js`
### 🟢 <ins>Step 8</ins>
In Discord, you can run either `/ping`, `/user`, `/server`. Any should count as running a **/** command to get the badge.
### 🟢 <ins>Step 9</ins>
Within 24 hours of running those, reguardless if the bot is still running, you can apply to get the Active Developer Badge on your profile [here](https://discord.com/developers/active-developer).
### ⚠️ <ins>Step 10</ins>
You can stop the script by pressing `Contorl+C` in the command line.

# Credits:
[Discord.js.org](https://discord.js.org/) for their basic bot creation guide.

[Click here and watch NTTS video on it](https://www.youtube.com/watch?v=PpYw7lQiNqI) (skip to 2:50 if you already have the bot ready from the developer panel)

[AlexFlipnote](https://github.com/AlexFlipnote/GiveMeBadge) for initial idea to make working version of a bot that serves the purpose of getting the badge.