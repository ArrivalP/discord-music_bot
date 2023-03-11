# discord-music_bot
Your Requirement to set up this bot 

Node JS Version upper or equal 16
VS Code

How to set up Music bot

Open this project in VS Code and choose new terminal and then setting project

```bash
npm i dotenv discord.js discord-player @discordjs/voice @discordjs/rest @discordjs/opus @discordjs/builders ffmpeg-static

```

then you setting bot in Discord Bot Developer and get token to set in file .env
https://discord.com/build/app-developers

after that you get discord bot ID to set in CliendID and your discord channel to get in GuildID in file index.js

```bash 
const CLIENT_ID ="your discord bot id"
const GUILD_ID ="your channel discord id"
```

then you run this in terminal

```bash
node index.js load //to setting your environment

npm start //start your bot working
```

Credit this project by https://www.youtube.com/watch?v=fN29HIaoHLU

Created at 11/03/2023
