---
title: Hubspot
permalink: /docs/hubspot/
---

<a name="hubspot"/>
#### [What you get with Hubspot Integration](#hubspot)
7Targets AI Sales Assistant is created as a user in **Hubspot** CRM.  
Leads/Contacts from **Hubspot** CRM can be assigned to 7Targets AI Sales Assistant directly within the Hubspot. AI Assistant will then own the lead, communicate and nurture to try and get the meeting. Assistant will also update the lead details putting engagement details (email, task) in Hubspot. 

One **important** point to note, as soon as the AI Assistant receives a response from the lead and detects it to be a Hot or Responded lead then the assistant assigns the lead back to the original owner.

<a name="Enabling 7Targets from Hubspot Marketplace"/>
#### [Authorize Hubspot for 7Targets ](#enabling-7Targets)
**Authorize Hubspot** button is available in **7Targets->View Profile-CRM Details** . Once Authorization is complete follow below steps for further configuration before it is ready to be used. 

1. Create your assistant in 7Targets if not already created. Provide the default values for context and other variables at the Assistant level by editing the Assistant.  
2. Create a user in Hubspot for your Assistant's email id.  
3. In 7Targets, under user profile, look at the "CRM Details" tab and click on "Verify Again" to get the acceptable status. Various status and the meanings are below:   
**ASSISTANT_EXISTS_AS_USER_IN_CRM** : You are all set. Go ahead and assign one contact from Hubspot to the Assistant user in Hubspot. That contact should be seen as lead in 7Targets in few seconds.  
**ASSISTANT_DOES_NOT_EXISTS_AS_USER_IN_CRM** : Follow step 2 and beyond above.  
**ASSISTANT_NOT_YET_CREATED** : Follow Step 1 onwards.  
**ALL_WORKING_WELL** : All set, it is working well for you.  
4. In Hubspot disable email notifications for the Assistant user.  
5. Verify in 7Targets that your Assistant has a Default Context. It is available on Edit Assistant page.
6. You are set, assign a contact/lead in Hubspot to the Assistant user and verify that you see that lead in 7Targets in the "Leads" page. 
7.  If you intend to pass context to the lead from Hubspot then create a custom field named "context" for Contacts in Hubspot. With this, when you assign the contact/lead to Assistant user and if there is any context provided for this contact/;ead then Assistant will use that else it will use the default context provided at the Assistant level in 7Targets. 
