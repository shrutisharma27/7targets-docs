---
title: HubSpot
permalink: /docs/hubspot/
---

<a name="hubspot"/>
#### [What you get with HubSpot Integration](#hubspot)
7Targets AI Sales Assistant is created as a user in **HubSpot** CRM.  
Leads/Contacts from **HubSpot** CRM can be assigned to 7Targets AI Sales Assistant directly within the HubSpot. AI Assistant will then own the lead, communicate and nurture to try and get the meeting. Assistant will update the communication details (email, task) in HubSpot for each contact she/he is nurturing. 

One **important** point to note, after AI Assistant is done with her job, she will assign the lead back to the original owner. 

<a name="enabling-7Targets"/>
#### [Setup Details for HubSpot and 7Targets](#enabling-7Targets)
**NOTE : HubSpot Admin level access is required to create a new user for Assistant in HubSpot. Org Admin access on 7Targets is required to sync the Assistant User from HubSpot.** 
If not already authorized yet then **Authorise** from HubSpot [Marketplace]( https://app.hubspot.com/ecosystem/6714307/marketplace/apps/sales/crm/7targets-ai-sales-assistant-208066 ) **OR** by clicking this link [authorise]( https://solution.7targets.com/hubspot-authorize). If you are already connected to Hubspot via some other Assistant in 7Targets then you are already authorised. You can still check it from **"Settings"->"CRM Details"**. Meaning of the status on the **CRM Details** page is explained below in the page. 
Once Authorisation is complete, follow below steps for further configuration. 

**1.** If *not* yet signed up or invited and created an Assistant in 7Targets. Please refer [Signup](/videos/home/#signup) and [Create Assistant](/videos/home/#create-assistant) . If user already created or invited then skip this step. Complete the onboarding of the user though.  
**2.** Create a user in HubSpot for your Assistant's email id. You can get the Assistant email id from the Edit Assistant page. Below screen shot has Assistant's email id as tara@7targets.7ts-d.com. Email is sent to the Assistant about joining HubSpot. Assistant forwards this email to the user, so that user can click the link and join HubSpot on Assistant's behalf. 
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

<a name="hubspot-7Targets-details"/>
#### [Details of Hubspot and 7Targets Integration](#hubspot-7Targets-details)

**How it works?**
- After the contact in Hubspot is assigned to the Assistant user in Hubspot, Assistant will own it for nurturing. Assistant will use the default Schedule and Context as configured in 7Targets. 
- Assistant will leave a note of confirmation like below image for the assigned contact.
![Confirmation Note from Assistant](../../../img/hubspot-7targets-confirmation-note.png)
- All the emails that Assistant sends or receives are logged in Hubspot too. Like in below image. 
![Logged Email by Assistant](../../../img/hubspot-7targets-email.png)
- After Assistant is done with her work, the contact is assigned back to the previous Contact owner. For example, if there is a response from the lead, then Assistant will stop further emails and assign it back to the previous owner. 

**Can I provide the context from Hubspot while assigning the contact to the assistant?**  
Yes. 7Targets adds a `Context` field to the Hubspot Contact and you can provide the value for it from Hubspot. If a value is provided then Assistant uses that instead of the default Context.  
**Can I see the 7Targets Lead status in Hubspot?**  
Yes. 7Targets adds a field `Lead Connection Status` to the Hubspot Contact and Assistant will keep it updated as the lead turn from Cold to Warm to Hot. You can add this field to your view or filter on it as required.  

<a name="7targets-lead-state-mapping-with-husbpot"/>
#### [Lead State to Hubspot Contact State Mapping](#7targets-lead-state-mapping-with-husbpot)
Assistant update the Hubspot Contact Status and Lead Connection Status as per the below mapping:

| 7Targets Lead State | Hubspot Contact Status | Lead Connection Status | 
|-------|--------|
| Cold | IN_PROGRESS | Cold |
| Engaged | IN_PROGRESS | Engaged |
| Warm | IN_PROGRESS | Warm |
| OutOfOffice | IN_PROGRESS | OutOfOffice |
| Hot | CONNECTED | Hot |
| Responded | CONNECTED | Responded |
| UnSubscribed | UNQUALIFIED | UnSubscribed |
| DeActivated | UNQUALIFIED | DeActivated |
| LeadAtRisk | CONNECTED | LeadAtRisk |
| Processed | QUALIFIED | Processed |
| Pending | In_Progress | Pending |
| New | NEW | New |


