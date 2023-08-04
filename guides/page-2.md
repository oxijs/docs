---
description: Setup page to start coding your bot
---

# Setup

## Installation

```bash
npm i oxi.js
```

## Example

```javascript
const oxi = require("oxi.js");

const client = new oxi.Bot({
    token: "Your token",
    prefix: "Your prefix",
    intents: ["GUILDS", "GUILD_MESSAGES"]
});

client.onMessage();

client.command({
  name: "ping",
  code: `Pong! $pingms`
}); // Command example
```
