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
For Sales Assistant, the default and out of box **Recommended** schedule comes with 7 followups over a 3-4 week period. User has an option of creating one or more schedules, called Custom schedule. Custom schedule lets one select among different tones for each followup. After a tone is selected one can get an idea of a sample message for that tone from the UI. At present the supported tones are Candid, Gentle, Appreciative, Hopeful, Assertive, Cautionary and Curious. If user does not want to use one of the generated email messages as per the tone, then user can select CUSTOM_MESSAGE and type own message to be used.  

You may have a lot of leads that you want to follow up and convert.  
Some leads may be close to you, some may be aware of your offerings, others may have seen a demo of your offerings and services, and rest may be strangers.  

It's important to nurture each of these sets of leads differently.  
This requires different schedules with different number of follow ups for each type of leads mentioned above. Click to find out [How to create custom schedule](#how-to-create-custom-schedule)  

<a name="assistant-adapt-email-send-time"/>  
#### [Adapt Email Send Time](#assistant-adapt-email-send-time) <a href="https://www.youtube.com/embed/-5YSFCvvUA4?rel=0" target="popup"  onclick="window.open('https://www.youtube.com/embed/-5YSFCvvUA4?rel=0','popup','width=700,height=500'); return false;"><i class='fa fa-youtube-play' style="color:red"></i></a>  
Assistant intends to send the email at such a time, that it has a better chance of opening. Assistant learns this from leads behavior and adapts sending of next email close to the time when lead may have opened the earlier email. Thus, the email is among the top few emails in the leads inbox.

<a name="assistant-add-lead-via-email"/>  
#### [Add Lead via Email](#assistant-add-lead-via-email)
If Sales Assistant is copied by the user in his/her communication with the lead then Assistant interprets this action as user wanting the Assistant to continue the followup and nurturing with the lead. 

**Two important Best Practice points:**  
- Add Assistant in the email (to or cc) with her name. e.g. **```Ashley <ashley@7targets.7ts-e.com>```** . The name is seen by the lead in the email, so it is best practice to ```put name along with the email id instead of just email id like above example```.
- ```Put the lead's email id with the name too, like above```. So that Assistant can interpret the lead's name from it. Else Assistant will use the part of the email before @ to address the lead.

**Some important points to note in this mode of assigning lead to assistant:**
- User will get an email with a time window to act/stop if he/she does not want assistant to send any email to the lead. In that case, user would have to Deactivate the lead.
- Assistant will use **Recommended for Email CC** schedule for leads from emails.
- This method of assigning/adding lead is available only for Sales Assistant.
- Assistant will not send the first introducing/connecting email from the schedule. Assistant will start only from the second email in the schedule.
- If there are more email ids in the original email from user then Assistant will pick the first email as Lead. Assistant will keep the rest in the loop.
- Assistant will send the first email after 3 days of adding the lead as per the schedule **Recommended for Email CC** unless your email indicates a different followup date (e.g. If you mention ```lets catchup in 2 weeks from now``` assistant will adjust the schedule accordingly).

<a name="assistant-add-lead-from-ooo"/>   
#### [Add Lead from Out of Office](#assistant-add-lead-from-ooo)   
If Sales Assistant extracts another email id from an Out of office response then the Assistant automatically adds that as a new lead and inform the user. User gets around 24 hrs to act and stop the assistant if she/he wants to. A new lead is added automatically only when the Out of office is more than 4 days from _now_. 

<a name="how-to-create-custom-schedule"/>  
#### [How to create custom schedule](#how-to-create-custom-schedule)   
Default schedule that is shipped with 7Targets is a '7 time followup' sequence within 3 weeks. 

For close friends, who are also potential leads, we recommend that you create a schedule of 3 to 4 follow ups; not more than that. You don't want to alienate your friends by following up too much. 

For those leads who are mildly interested, but are on the fence on whether to go ahead with your offering or not, they need more information about your offering and you want to remind them on a slow schedule but for a longer duration of time. 

Here are the steps on how to create a new schedule:  
Decide a set of leads of similar characteristics  
Decide how many times you want to followup this set of leads  

The schedules created by 7Targets are followup schedules. If you want to mix it with a custom messages in between followups, decide your custom messages. One of the steps below will address how you can add custom messages to auto generated ones.

Finally, choose an existing schedule that is closest to the schedule you are trying to create.   
First, change the name of the schedule. Here is a good naming strategy. You can have your own strategies.  

[Eg. 1] If I am selling Cloud Migration, and if this schedule is for new event leads, I would name the schedule 
'FollowupScheduleForCloudMigrationForNewEventLeads'

The name has a combination of Offering, LeadStatus and LeadSource. 

[Eg. 2] If your offering is Digital Transformation, your schedule name will look like
FollowupScheduleForDigitalTransformationForNewEventLeads

[Eg. 3] If lead source is reference, 
FollowupScheduleForDigitalTransformationFromReferences

Set number of followups 
User the + and delete buttons to add rows and remove rows. Each row represents one followup. Each followup message can be seen when you click the 'eye icon'. The followup message used for that step is a auto generated message. Hence the message will change each time, and will still retain the context of the message. This is done to reduce the chances of showing up in spam radars. 

Add custom message   
- If you want to override the auto-generated message in some (or all) portions of the followups, you can easily do so.   
- Click on this column and choose 'custom message' from the drop down.   
- Click on the 'eye icon'.   
- Click the 'pencil icon' to get into edit mode.   
- IMPORTANT: Name your message!! These names are used later on in other schedules to quickly select that message.   
- Paste your message into the edit box.   
- Save the message  
- IMPORTANT: Choose the drop down of message names and choose the message you want to select for that row.   

Verify the schedule  
Now, add a lead. Choose this new schedule when you add this lead. Verify that you are able to see the messages from this schedule in the Lead expansion view. 
