---
id: api-stats
title: Statistics API
custom_edit_url: https://github.com/AirReps/website-content/blob/edit/api-stats.md
---

:::warning
This area is still under construction
:::

:::tip
The best way to get continued support and the latest news about AirPods
replicas, is to [join our discord!](https://airreps.link/discord)
:::


# Overview
This endpoint is used to get data about the api including version and performance statistics.

# Methods
## `/stats`
> Returns an object with the current statistics of the api server.  
## `/stats/endpoint`
> Returns an object with the current statistics of the specific endpoint.

### Use Case
Getting information about the api.

### Request
```shell
    GET https://api.airreps.info/stats
    GET https://api.airreps.info/stats/endpoint
```
### Parameters
None accepted  

### Response
#### /stats
Returns a JSON body with:
* CPU Usage
* Memory Usage
* API Version

```java
  {
   "cpu_usage":"4.031465093256939%",
   "memory_usage":31539200,
   "version":1.2
  }
```
#### /stats/endpoint
Returns a JSON body with:
* Usages

```java
  {
   "usages":22
  }
```

### Example
**[Try /stats here](https://apitester.com/shared/checks/945089efb81445d48fcd60c3e8124a8e)**  
**[Try /stats/endpoint here](https://apitester.com/shared/checks/e3e7ac72e1cf4451992c643912b212bb)**
