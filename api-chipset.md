---
id: api-chipset
title: Chipset API
custom_edit_url: https://github.com/AirReps/website-content/blob/edit/api-chipset.md
---

:::warning
This area is still under construction
:::

:::tip
The best way to get continued support and the latest news about AirPods
replicas, is to [join our discord!](https://airreps.link/discord)
:::


# Overview
This endpoint is used to get the current/latest documentation for a bluetooth chipset that is in some way related to airpod replicas or has relatives (same family) that are. 

For example, AB1536 is used in replicas, so AB1530 will also be listed in the database. We are constantly updating the database with new chipsets.

# Methods
## `/chipdoc`
> Returns an object with the current status of the AirReps discord server.

### Use Case
Query the current state of AirReps' discord server

### Request
```shell
    GET https://api.airreps.info/chipdoc
```
### Parameters
|**Required**|
|----|----|----|----|
||Query Param|Type - Description|Example Value|
| |`chip`|String - accepts a chipset id|`AB1530`|

### Response
Returns a JSON body with:
* Link to document location
* Status message

```java
    {
        "link": String,
        "status": String,
    }
```

### Example
**[Try it here](https://apitester.com/shared/checks/c7b55ed92c5c4f419ec56d74c0189bfb)**
