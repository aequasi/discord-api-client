# Discord API Client

## Installation

```bash
$ npm install --save discord-api-client
```

## Usage

```typescript
import {Client, Endpoints} from "discord-api-client";

// There are a couple of other options in here, make sure you check them out.
const client = new Client({
    token: "Bot <DISCORD API TOKEN HERE>"
});

const response = await client.request("GET", Endpoints.GATEWAY_BOT);

console.log(response);
```
