---
category: Lead
url_path: 'https://api.7targets.com/leads'
title: 'Create a Lead'
type: 'POST'

layout: apis
---

This method creates a Lead for the Assistant to process.

### Request

* The headers must include a **valid authentication token**.
* **The body can't be empty** 

```Authentication: Bearer <TOKEN>```
```{
    name: "John",  //Mandatory
    lastName: "Doe", 
    type: "SALES", //Mandatory One of WHATSAPP or SALES
    source: "Website", //Mandatory
    context: "AI Sales Assistant", //Assistant will write message using this
    email: "john.doe@gmail.com", //Mandatory if type is SALES
    phone: "+919123456789", //Mandatory if type is WHATSAPP
    scheduleId : <valid schedule Id>, //Optional. If not provided then use default
    assistantId : <your assistant Id> //Mandatory
}```

### Response

**If succeeds**, returns the created Lead.

```Status: 201 Created```
```{
    id: 2345,
    name: "John",   
    lastName: "Doe", 
    type: "SALES", 
    email: "john.doe@gmail.com", 
    phone: "+919123456789", 
    scheduleId : <valid schedule Id>,
    assistantId : <your assistant Id>,
    nextScheduleTime : <date and time the message will be send>,
    state : Cold,
    subState : Followup_1
}```