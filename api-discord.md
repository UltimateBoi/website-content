---
id: api-discord
title: Discord API
custom_edit_url: https://github.com/AirReps/website-content/blob/edit/api-discord.md
---

:::warning
This area is still under construction
:::

:::tip
The best way to get continued support and the latest news about AirPods
replicas, is to [join our discord!](https://airreps.link/discord)
:::

# Overview
Provides functionality to interact with AirReps discord server.

## `/members`
>Returns an object with the current status of the AirReps discord server.

### Use Case
Query the current state of AirReps' discord server

### Request
```shell
    GET https://api.airreps.info/members
```
### Parameters
None accepted

### Response
Returns a JSON body with:
* Total members
* Status message
* Server name
* Number of members which are appearing online

```java
    {
        "count": Number,
        "status": String,
        "server": String,
        "online": Number
    }
```

### Example
**[Try it here](https://apitester.com/shared/checks/90965ee841c8457582810607d04aa329)**