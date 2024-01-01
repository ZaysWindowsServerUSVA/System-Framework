# System-Framework
Create a discord bot without the use of discord

# Installation
`npm i systembot-framework`

# Usage

```
const { Client } = require("systembot-framework");
const client = new Client(
    {
        botid: "id",
        bottoken: "token"
    },
    {
        CloseAllProcessAfterEnd: false,
        CreateLogFilesWhenReady: false,
        AllowCustomizedErrorHandler: true,
        AllowCustomizedDiscordErrorHandler: true,
        StartupOps : {
            AllowLoadMsg: true,
            AllowAnnoymousServerUpdates: false
        }
    }
)
```
