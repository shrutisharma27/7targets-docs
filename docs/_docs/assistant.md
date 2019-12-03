---
title: Assistant
permalink: /docs/assistant/
---

<a name="assistant-types"/>
## [Assistant Types](#assistant-types)
7Targets provides 3 types of assistants
- Sales Assistant 
- AMC Assistant 
- WhatsApp assistants  
Each assistant has a different role and responsibility.  

<a name="sales-assistant"/>
#### [Sales Assistant](#sales-assistant)
Sales Assistant has the responsibility of communicating with the lead over email with an intent of getting a meeting with the lead. More suitable for Sales people who use email as primary mechanism of communication. The default recommended schedule comes with 7 follow-ups with increasing duration between the follow-ups. User has an option to use custom schedule too for this assistant type. 

If the user want to use different schedule than the out of  box **Recommended** schedule then create a new **Custom Schedule**. Decide the number of followups and the time between each followup, give a proper name and description, then save it. The custom schedule created will be available for selection while adding a new lead. If required change the newly created custom schedule to default schedule so that all the leads added uses it by default. 

<a name="whatsapp-assistant"/>
#### [WhatsApp Assistant](#whatsapp-assistant)  
WhatsApp assistant can discover the leads from your WhatsApp number and start following up if there is no response from the lead to any of your comments even after 2 days of posting the message to the lead. Leads can also be added from the UI. This is purely WhatsApp only communication. Today the assistant does 3 follow-ups after sending the initial message and this cannot be changed. 

<a name="amc-assistant"/>
#### [AMC Assistant](#amc-assistant)
AMC Assistant is responsible for remembering the AMC date and try and keep the lead interested till we reach near the AMC renewal date, then try and get meeting with the lead. Communication is over email. 

<a name="assistant-custom-schedule"/>  
#### [Custom Schedule](#assistant-custom-schedule)  
For Sales Assistant, the default and out of box **Recommended** schedule comes with 7 followups over a 3-4 week period. User has an option of creating one or more schedules, called Custom schedule. Custom schedule lets one select along different tones for each followup. After a tone is selected one can get an idea of a sample message for that tone from the UI. At present the supported tones are Candid, Gentle, Appreciative, Hopeful, Assertive, Cautionary and Curious.

<a name="assistant-adapt-email-send-time"/>  
#### [Adapt Email Send Time](#assistant-adapt-email-send-time)  
Assistant intends to send the email at such a time, that it has a better chance of opening. Assistant learns this from leads behavior and adapts sending of next email close to the time when lead may have opened the earlier email. Thus, the email is among the top few emails in the leads inbox.

<a name="assistant-add-lead-via-email"/>  
#### [Add Lead via Email](#assistant-add-lead-via-email)
If Sales Assistant is copied by the user in his/her communication with the lead then Assistant interprets this action as user wanting the Assistant to continue the followup and nurturing with the lead. Some important points to note in this mode of assigning lead to assistant:
- Add Assistant in the email (to or cc) with her name. e.g. "Ashley \<ashley@7targets.7ts-e.com\>" . The name is seen by the lead in the email, so it is best practice to put name along with the email id instead of just email id.
- Put the lead's email id with the name too, like above. So that Assistant can interpret the lead's name from it. Else Assistant will use the part of the email before @ to address the lead.
- User will get an email with a time window to act/stop if he/she does not want assistant to send any email to the lead. In that case, user would have to Deactivate the lead.
- Assistant will use **Recommended for Email CC** schedule for such the lead.
- This method of assigning/adding lead is available only for Sales Assistant
- Assistant will not send the first introducing/connecting email from the schedule. Assistant will start only from the second email in the schedule.
- Assistant will keep the original email from user to the lead in her first email (2nd as per schedule) to maintain the context.
- Assistant will pick the first non user email as Lead. If there are more email ids in the original email from user, Assistant will maintain them too along with the user in her emails.
- Assistant will send the first email after 3 days of adding the lead as per the schedule **Recommended for Email CC** . But if user mentions some date which is more than 3 days then Assistant will schedule the followup on that date (e.g. Lets catchup in 2 weeks from now)

<a name="assistant-add-lead-from-ooo"/>  
#### [Add Lead from Out of Office](#assistant-add-lead-from-ooo)
If Sales Assistant extracts another email id from an Out of office response then the Assistant automatically adds that as a new lead and inform the user. User gets around 24 hrs to act and stop the assistant if she/he wants to. A new lead is added automatically only when the Out of office is more than 4 days from _now_. 
