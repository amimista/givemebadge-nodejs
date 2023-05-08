# Active Developer Badge Discord Bot

## Basic Usage
1. Make sure that LTS Node.JS is installed on your computer.
2. Extract this repo and open a command line in the folder
3. In the command line, run `npm install` to get required dependancies
4. Create `config.json` and insert your the **token of your application**, **application ID**, and the **guild ID**
    - Should look something like this
    ```json
    {
        "token":"<TOKEN>",
        "clientId": "<CLIENTID>",
        "guildId": "<GUILDID>"
    }
    ```
    - Find the token of your App in the Discord Developers' Portal
        - You may need to regenerate to copy it
    - You can find the application ID also in the Discord Developers' Portal
    - Provided you have developer mode enabled on the Discord client, you can right click the server icon on the left and copy the guild ID.
5. In the command line, run `node deploy-commands.js` then run `node index.js`
6. In Discord, you can run either `/ping`, `/user`, `/server`. Any should count as running a **/** command to get the badge.
7. Within 24 hours of running those, reguardless if the bot is still running, you can apply to get the Active Developer Badge on your profile.