---
title: Zoho
permalink: /docs/zoho/
---

<a name="zoho"/>
#### [What you get with Zoho Integration](#zoho)
7Targets AI Sales Assistant is created as a user in **Zoho** CRM.  
Leads/Contacts from **Zoho** CRM can be assigned to 7Targets AI Sales Assistant directly within Zoho. AI Assistant will then own the lead, communicate and nurture to try and get the meeting. Assistant will update the communication details (emails) in Zoho for each contact she/he is nurturing. 

One **important** point to note, after AI Assistant is done with her job, she will assign the lead back to the original owner. 

<a name="Enabling 7Targets from Zoho Marketplace"/>
#### [Setup Details for Zoho and 7Targets ](#enabling-7Targets)
**NOTE : Zoho Admin level access is required to create a new user for Assistant in Zoho. Org Admin access on 7Targets is required to sync the Assistant User from Zoho.** 
If not already installed the extension yet then **Install** from Zoho [Marketplace]( https://marketplace.zoho.com/home ). After installing, the extension will open a new tab page where you will have to authorize 7Targets to connect with Zoho CRM. If you are already connected to Zoho via some other Assistant in 7Targets then you are already authorised. You can still check it from **"Settings"->"CRM Details"**. Meaning of the status on the **CRM Details** page is explained below in the page. 
Once Authorisation is complete, follow below steps for further configuration. 
![Assign to Assistant](../../../img/install-extension-zoho.png)

**1.** If *not* yet signed up or invited and created an Assistant in 7Targets. Please refer [Signup](/videos/home/#signup) and [Create Assistant](/videos/home/#create-assistant) . If user already created or invited then skip this step. Complete the onboarding of the user though.  
**2.** Create a user in Zoho for your Assistant's email id. You can get the Assistant email id from the Edit Assistant page. Below screen shot has Assistant's email id as tara@7targets.7ts-d.com.
![Assistant's email](../../../img/assistant-email.png)
**3.** Go to **"Settings"->"CRM Details"** in 7Targets. By clicking the Refresh button lets verify if the Assistant user is created in Zoho and we are ready to move ahead. Against each Assistant you will see the CRM Integration Status. ![CRM Integration Status](../../../img/crm-integration-status.png)

Meaning of CRM Integration Status:  
**ASSISTANT_EXISTS_AS_USER_IN_CRM** : You are all set. Go ahead and assign the contact from Zoho to the Assistant user in Zoho. That contact should be seen as lead in 7Targets in few seconds. Assistant should also update the note for the contact that she is going to work on it.  
**ALL_WORKING_WELL** : All set, it is working well for you. You have already assigned contact in Zoho to the Assistant and she is working on it too.  
**ASSISTANT_DOES_NOT_EXISTS_AS_USER_IN_CRM** : Go back to step 2 above. If still facing issues drop an email to support@7targets.com.  
**ASSISTANT_NOT_YET_CREATED** : Follow Step 1 onwards.   

**4.** Verify in 7Targets that your Assistant has a Default Context. It is available on Edit Assistant page. Default context is used by the Assistant to write an email. You can check how the context is used by Assistant when writing an email. Just try to add a new lead from 7Targets. Other default values can be filled too. 
![Default Context](../../../img/assistant-defaults.png)
**5.** You are all set, assign a contact/lead in Zoho to the Assistant user and verify that you see that lead in 7Targets in the "Leads" page. 
![Assign to Assistant](../../../img/assign-to-assistant-zoho.png)
**6.**  If you intend to pass context to the lead from Zoho then use the custom field named "7Targets Context" for Contacts in Zoho. With this, when you assign the contact/lead to Assistant user and if there is any context provided for this contact/lead then Assistant will use that else it will use the default context at the Assistant level in 7Targets.
![Context from Zoho](../../../img/context-in-zoho.png)

**Feel free to reach out to support@7targets.com for any help required in setup**
