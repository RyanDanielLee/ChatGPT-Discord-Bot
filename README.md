#ChatGPT Discord Bot
A simple discord bot made using node js that consumes the chatgpt 3.5 API

<h2>Getting Started</h2>

Go to https://discord.com/developers/applications to create a bot


Then, generate a link to invite your bot to a server


<h2>Code</h2>
After installing the preset files, you want to create a file named `.env` This file will store your bot token and API keys. Make sure this file is in your root directory


![image](https://user-images.githubusercontent.com/105259018/232950383-d5dd7573-b065-44dc-85dc-f15b0a7c55d0.png)


Go back to your discord dashboard and obtain the bot's token and paste it into the `.env` file


Then, head over to https://platform.openai.com/account/api-keys to obtain your OpenAI key and paste it into your `.env` file.

Lastly, go to your discord client and right click on whichever channel you want the bot to type in. Click on "Copy Channel ID" and paste it into the .env file.


<h2>Node Packages</h2>
Please install the required node package modules in your terminal
`npm install discord.js openai dotenv`


To start your bot, use the command `node index.js` in your terminal


<h2>24/7 Bot Hosting For Free</h2>
Go to https://discloudbot.com/dashboard and add an app



In `discloud.config` change the name of the bot to whatever you want


Zip your files and upload to discloud, and run your app.
