# discord_extractor

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Setup Steps:
Head to the Discord Developer Portal and Log In. (https://discord.com/developers/applications)
Click "New Application"
Give the Application a Name and click Create
On the left side click on "Bot" and then on "Add Bot" on the new page.
Confirm with "Yes, do it!"
Uncheck "Public Bot"
Check "Server Members Intent"
Check "Message Content Intent"
Save changes.
Go to OAuth2 -> URL Generator.
Under "Scopes" check "bot"
Under Bot permissions check "Read Messages/View Channels" and "Read Message History".
Visit the link that is shown under "Generated URL"
Choose the server you want to add the bot to and click "continue". Finish adding the bot by clicking "Authorize".
Go to "Bot" and click on "Reset Token".
Fill in the Token in the boxe below and click Start.
