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
1. Head to the Discord Developer Portal and Log In. (https://discord.com/developers/applications)
2. Click "New Application"
3. Give the Application a Name and click Create
4. On the left side click on "Bot" and then on "Add Bot" on the new page.
5. Confirm with "Yes, do it!"
6. Uncheck "Public Bot"
7. Check "Server Members Intent"
8. Check "Message Content Intent"
9. Save changes.
10. Go to OAuth2 -> URL Generator.
11. Under "Scopes" check "bot"
12. Under Bot permissions check "Read Messages/View Channels" and "Read Message History".
13. Visit the link that is shown under "Generated URL"
14. Choose the server you want to add the bot to and click "continue". Finish adding the bot by clicking "Authorize".
15. Go to "Bot" and click on "Reset Token".
16. Fill in the Token in the boxe below and click Start.
