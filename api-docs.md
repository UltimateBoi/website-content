---
id: api-docs
title: Api documentation
custom_edit_url: https://github.com/AirReps/website-content/blob/edit/api-docs.md
---

:::tip
The best way to get continued support and the latest news about AirPods
replicas, is to [join our discord!](https://airreps.link/discord)
:::

## **Overview**  
### **Introduction**  
This API does only use the **GET** method for all open endpoints. This means that you can add the parameter you want to send to the server in a **request** in the URL, for example: ``https://KindImpoliteExperiments.albinhedwall.repl.co/endpoint?thing=isEqualToThis``.  
  
You can also add multiple parameters by using ``&`` between every parameter, like this: ``/endpoint?thing=isEqualToThis&anotherThing=isThisValue``  
### **Base URL**  
The base URL is right now ``https://KindImpoliteExperiments.albinhedwall.repl.co``  
This might change in a future release.  
### **Why am I getting an error like: "missing "x" parameter?**  
This means that you have forgot to add a value to the **GET** request. For example, you might have forgot to add the chipset model or something else after the endpoint.  
### **End Points**  
#### **members**  
##### Description  
This endpoint is for getting basic info from the AirReps discord server including total members and the number of members that are not offline or invisible (online).  
##### Information  
» Endpoint: ``/members``  
» Method: ``GET``  
» Required Parameters:  
``None``  
» Returned data example:  
```json
{
    "count": 7055,
    "status": "success",
    "server": "AirReps",
    "online": 974
}
```  
#### **Chipset documentation**  
##### Description  
This endpoint is used to get the current latest documentation for a bluetooth chipset that is in some way related to airpod replicas or has relatives (same family) that are. For example, AB1536 is used in replicas, so AB1530 will also be listed in the database. We are comstantly updating the database with new chipset, you migth even find info on some unreleased ones.  
##### Information  
» Endpoint: ``/chipdoc``  
» Method: ``GET``  
» Required Parameters:  
``chip``  
» Returned data example:  
```json
{
    "link": "https://airreps.info/files/datasheets/AB1561_AB1562_Datasheet.pdf",
    "status": "success"
}
```  
