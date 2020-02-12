---
title: Releases
permalink: /releases/home/
redirect_from: /releases/index.html
---

### 12 Feb 2020
```
- Pending filter added in leads list.  
- Text changed for force send confirmation modal, styling fixed.  
- Ellipsis for the context in lead cards will show hover on the tooltip.  
```

### 12 Feb 2020
```
- Force Send the Pending Email Validation leads cautiously.  
- All the places for user to type emails have same look and feel now.  
```
### 11 Feb 2020
```
- Native Hubspot OAuth2 based integration. 7Targets can be on Hubspot marketplace now. 
- Simplify Introduce me.
- Show lead count in today's followup.
- Visually identify the schedules not owned by self.
```

### 29 Jan 2020
```
- Improved UI for Schedule and Nurturing on Desktop.  
- Assistant to remind the Sales person for Responded and Hot Leads. If no response from sales person then Assistant marks the lead at risk. Sales person has an option to set reminder after days.  
- See all the possible emails while adding lead and edit any of those emails as per schedule. 
```

### 20 Jan 2020
```
- Users would be able to access/use schedules created by others users from the same Organisation. 
- Possibly invalid email is kept under review for validation. 
```

### 17 Jan 2020
```
- Assistant to have a default schedule for leads from EmailCC. User can now decide the schedule to use for such leads.
- User can send an image to the WhatsApp leads when using that assistant.
- Simplified Add and Edit lead on mobile.
```

### 14 Jan 2020
```
- Custom Schedule capability for WhatsApp leads
- Allow to bulk upload many lead but process only few(~50) per day for WhatsApp leads. 
- Ability to edit and restart followup for WhatsApp Leads
- Recommended Sales Assistant Schedule, first email goes after 1 day of adding the lead.
```

### 07 Jan 2020
```
- Ability to edit the scheduled message for the lead in the timeline view.  
- Take actions like Add Notes, Mark Hot, etc on multiple leads, on desktop view only.
- Processed Lead can be Restarted for followup. 
```


### 31 Dec 2019
```
- Leads created from EmailCC (or others too) can be edited for all fields other than email address.
- When leads in Hubspot CRM is assigned to the assistant then Assistant will check if any email is sent by user to the lead. If user has sent any email then Assistant will not send the first email and will use the same email subject and email body as quoted text below the emails Assistant will write. 
- Assistant level attribute to enable/disable accepting leads via EmailCC.
- Followup for the Processed leads can be restarted by Editing the lead.
```

### 20 Dec 2019
```
- Schedule can have a type CUSTOM_MESSAGE so that user can type in his message if he wants to. Useful for scenarios when user wants to add multiple leads from CRM and want to have a custom first message to go out instead of generated. This would be anyways possible from within 7Targets UI but if user is doing it from a CRM then it would not have been possible. 
```

### 16 Dec 2019
```
- Assistant can be provided the Primary offering which will  be used as context in the Lead communication if the context is empty at the lead level. Can be overwritten while adding a new lead.
```

### 10 Dec 2019
```
- Ease of traversing messages on timeline view.
- Assign the leads in Hubspot to your 7Targets AI Assistant for nurturing
```

### 03 Dec 2019
```
- Improved identification of Warm and Engaged leads to reduce false positives
- Show all the email ids in the received email by the assisant. In UI as well as in the email forwarded to the user by the assistant. 
```

### 03 Dec 2019
```
- Add Lead via Email
- Add Lead from Out of Office  
- Ease of onboarding the Assistant in CRM. The email sent to the assistant's email if from CRM is now forwarded to the 7Targets support group.
```

### 25 Nov 2019
```
- Now you can use Reference as lead source. Assistant is trained to generate message for such source. 
```

### 21 Nov 2019
```
- Quickly know the number of Warm and Engaged leads from the dashboard. Click on it to get to the exact list too in the lead list.
```

### 19 Nov 2019
```
- Nurture the lead by adding your own PS statements. Helps provide answers for "Did you know". One can put Customer stories, white papers, video links, etc to the assistant and then assistant will use one at a time in the emails she sends. 
- Securely Subscribe using Stripe. 
```

### 14 Nov 2019
```
- Assistant uses the AI sense to extract some important information like email, phone, company, etc and show it to the user
- Engaged leads identification got smarter
```

### 11 Nov 2019
```
- Smart followup for out of office Lead. Assistant will align the followup email date based on the number of days of OOO.
- User can now edit the email subject while adding lead.
- User will be provided with subject which are working based on analytics (i.e. emails are being opened).
```

### 7 Nov 2019
```
- Assistant will notify the user on email and WhatsApp at the right time about the engaged leads, so that the user can call the lead at that moment.
```

### 22 Oct 2019 
```
- Ability to provide Additional Information Line to the Assistant for getting more context in the email. 
- Received Response email sent to the boss, to contain a link to open that lead and get introduced. 
```

### 18 Oct 2019 
```
- Spreading out leads creation while excel import. 
- Avoid debounce concurrent calls to not get into the concurrent call limit. Also handle the return code for this.
- Fixed some failures in Hot and Deactivate detection.
- Schedule Message shown in the timegraph now conveys that this is a Possible Message to be sent. 
- IntroduceMe URL and Lead State in the Forwarded Lead Response email
```
### 14 Oct 2019 
```
- Know if and when the email was opened by the lead.
- Adaptive email sending time, based on when the user reads the email.
- Ability to know the opened follow-up email in the timeline graph for a specific lead
- Tone based scheduled messages. User can pick the tone to be used while creating a custom schedule.
- Ability to include Offer in the custom schedule.
```

### 01 Oct 2019 
```
- On click of the Lead Responses and Todays Followup in dashboard, the lead is opened in context
- BCC all the emails sent by the SALES assistant to the provided email id.
```

### 25 Sept 2019 
```
- Help website for 7Targets AI Assistant
```

### 24 Sept 2019 
```
- Show the possible messages to be sent in the timeline graph as per the future schedule
- Context is searchable in the Add Lead. So that user can reuse his last typed context.
```

### 23 Sept 2019 
```
- User can now decide to include or not unsubscribe and whatsapp link in the email below signature
- When integrated with 3rd party CRM, then do not allow to change the assistant name.
- Video help added for few functions. Not available on mobile view.
- Few important fixes
```

### 13 Sept 2019 
```
- Lead deactivated because of Invalid WhatsApp number should convey it in the UI too
- /sign-up direct URL so that new users avoid one click and our ads can directly take the user to signup page
- Allow schedule gap to be as high as 30 days. As well allow the schedule to be over 340 days
- Mobile view, click on Hot in dashboard should take to Hot leads in the list
- Remember between Month, Quarter, Year in dashboard across the other menu clicks
```

### 11 Sept 2019 
```
- WhatsApp Assistant login failure should be notified with different subjects and copy 7Targets support
- Ability to add User Note from UI for each lead
- Show Deactivated reason on mobile view too
- In Timeline graph, open the message even when user clicks on the circles
- Allow user to send the Introduce Me email even when there is no response from the lead
```

### 4 Sept 2019
```
- Assistant can be assigned a lead directly from **Pipedrive**
- Show deactivation reason in UI
- User Note for manually marked Hot leads
- While add lead, let user pick schedule date as far as 9 months later
- Send the OOO email to the user like other emails received
- For add lead, last name should not be mandatory
```
### 25 Aug 2019
```
- Assign lead to the Assistant directly from **Salesforce**
- Admin to be able to write the Weekly Summary email text
- User has the ability to create and user **Custom schedule**
- WhatsApp messages can contain newlines now 
- Ability to schedule sending email to the added lead at a later time 
- WhatsApp followup messages are more non-formal and small
```
### 10 Aug 2019
```
- Admin UI for the user leads report
- Handle network outage in the UI
- Assistant to respond with brochure automatically when asked for
- Shared calendar URL in the VA Signature
```

### 29 July 2019
```
- Post User onboarding. Activate WhatsApp Assistant from the Admin UI
- Bulk upload notification to user in email 
- WhatsApp change of intent from call to response
- Remove unsubscribe action in UI for the WhatsApp Assistant leads
```

### 25 July 2019
```
- Bulk upload for WhatsApp VA
- Defect fixes for WhatsApp VA 
- Allow edit of first message while adding lead
```
### 17 July 2019
```
- WhatsApp Sales Assistant released
```
### 15 June 2019 and Earlier
```
- AMC Assistant released
- In AMC Assistant ability to receive all the communication between Assistant and Lead on a BCC email id
- Phone meeting and Face to Face meeting as Lead Source when adding a new lead
- Bulk Lead upload/add via excel file
- Each user has reference code which he can give to people he refers to
```
