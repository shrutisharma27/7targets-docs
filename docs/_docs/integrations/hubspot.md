---
title: HubSpot
permalink: /docs/hubspot/
---

<a name="hubspot"/>
#### [What you get with HubSpot Integration](#hubspot)
7Targets AI Sales Assistant is created as a user in **HubSpot** CRM.  
Leads/Contacts from **HubSpot** CRM can be assigned to 7Targets AI Sales Assistant directly within the HubSpot. AI Assistant will then own the lead, communicate and nurture to try and get the meeting. Assistant will update the communication details (email, task) in HubSpot for each contact she/he is nurturing. 

One **important** point to note, after AI Assistant is done with her job, she will assign the lead back to the original owner. 

<a name="Enabling 7Targets from HubSpot Marketplace"/>
#### [Setup Details for HubSpot and 7Targets ](#enabling-7Targets)
If not already authorized yet then **Authorise** from HubSpot Marketplace **OR** by clicking this link [authorise]( https://solution.7targets.com/hubspot-authorize). Once Authorisation is complete, follow below steps for further configuration. 

**1.** If *not* yet signed up or invited and created an Assistant in 7Targets. Please refer [Signup](/videos/home/#signup) and [Create Assistant](/videos/home/#create-assistant)  
**2.** Create a user in HubSpot for your Assistant's email id. You can get the Assistant email id from the Edit Assistant page. Below screen shot has Assistant's email id as tara@7targets.7ts-d.com. Email is sent to the Assistant ab out joining HubSpot. Assistant forwards this email to the user, so that user can click the link and join HubSpot on Assistant's behalf. 
![Assistant's email](../../../img/assistant-email.png)
**3.** Go to **"Settings"->"CRM Details"** in 7Targets. By clicking he Refresh button lets verify if the Assistant user is created in HubSpot and we are ready to move ahead. Against each Assistant you will see the CRM Integration Status. ![CRM Integration Status](../../../img/crm-integration-status.png)

Meaning of CRM Integration Status:  
**ASSISTANT_EXISTS_AS_USER_IN_CRM** : You are all set. Go ahead and assign the contact from HubSpot to the Assistant user in HubSpot. That contact should be seen as lead in 7Targets in few seconds. Assistant should also update the note for the contact that she is going to work on it.  
**ALL_WORKING_WELL** : All set, it is working well for you. You have already assigned contact in HubSpot to the Assistant and she is working on it too.  
**ASSISTANT_DOES_NOT_EXISTS_AS_USER_IN_CRM** : Go back to step 2 above. If still facing issues drop an email to support@7targets.com.  
**ASSISTANT_NOT_YET_CREATED** : Follow Step 1 onwards.   

**4.** In HubSpot, disable email notifications for the Assistant user from Settings. This is to avoid  unnecessary emails to the Assistant. 
![disable email notifications](../../../img/disable-email-notifications.png)

**5.** Verify in 7Targets that your Assistant has a Default Context. It is available on Edit Assistant page. Default context is used by the Assistant to write an email. You can check how the context is used by Assistant when writing an email. Just try to add a new lead from 7Targets. Other default values can be filled too. 
![Default Context](../../../img/assistant-defaults.png)
**6.** You are all set, assign a contact/lead in HubSpot to the Assistant user and verify that you see that lead in 7Targets in the "Leads" page. 
![Assign to Assistant](../../../img/assign-to-assistant.png)
**7.**  If you intend to pass context to the lead from HubSpot then use the custom field named "Context" for Contacts in HubSpot. With this, when you assign the contact/lead to Assistant user and if there is any context provided for this contact/lead then Assistant will use that else it will use the default context at the Assistant level in 7Targets. Note that Assistant will update back a custom field named "Lead Connection Status" in HubSpot.
![Context from HubSpot](../../../img/context-in-hubspot.png)

**Feel free to reach out to support@7targets.com for any help required in setup**
