# h3bot
Open source Discord bot, written and maintained by me, Not_H3. 

H3bot is a Discord bot written using the Discord.JS framework, it is written in TypeScript instead of regular JavaScript because that's what I personally prefer for bots. 

# Usage and installation
It's very to install h3bot, just follow the following steps as shown below:
```bash
# Cloning the git repo
git clone https://github.com/damger9/h3bot.git

# Entering the freshly made directory
cd h3bot

# Installing the needed libraries to run the bot
npm install 

# Creating the neccesary config.json
cd src
cp example-config.json config.json
# You can also manually create a config.json, keep in mind it has to be called config.json!

# In the config.json, set your token, clientID and serverID
# ^- only if developmentMode is set to true 

# Running your instance of h3bot
cd ../
npm run start

# Your instance of h3bot is now active and working! 
# If you find any bugs please report them asap!
```

If you don't have git installed you can manually download the .zip file and follow- the remainder of the steps after that. 