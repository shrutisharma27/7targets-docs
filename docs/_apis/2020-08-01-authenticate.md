---
category: Authenticate
url_path: 'https://solution.7targets.com/api/authenticate'
title: 'Authenticate'
type: 'POST'

layout: null
---


This method authenticate and returns the Auth token to be used in further API calls.

### Request

* **The body can't be empty** and must include username and password attribute.  
* rememberMe is optional, if provided value is **true** then the token received is valid for 10 days.

```{
    username: "<your login email on 7targets>"
    password: "<your password>"
}```

### Response

**If succeeds**, returns the auth token to be used in further API calls

```Status: 200```
```{
    id_token: <your auth token>
}```