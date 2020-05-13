---
title: Releases
permalink: /releases/home/
redirect_from: /releases/index.html
---

### 13 May 2020
```
- Hot categorization model improvements. 
- Upload to show the correct uploaded number in the upload history page.
- Consolidate state ann derived state filter in lead list in one accordion. 
- Default owner for leads from HubSpot. So that if the contact/lead was directly assigned to Assistant and no history of previous owner is found in HubSpot, then assign the lead to the default owner.
- When leads are added in 7Targets directly, but then later on assigned to the assistant from CRM, should be restarted for processing. 
- Show the user email in Notify Me under Notifications. 
- Fix for weekly summary email not working. 
- In bulk lead at times when it is stuck in Validating, user is blocked for uploading another excel file. A cancel options in the UI allows the user to stop and then upload a new file.
- In excel upload convert the first character of first and last name to capital.
- Option to see the raw response received. To handle scenarios where the received response could not be processed correctly and user looses some important information. 
```
### 08 May 2020
```
- Notification preference for each type of notification. With ability to copy someone else and remove self if required.
- Ability to take lead out of LAR when received response or while updating the status or adding notes from UI.
- Weekly summary email. Don't show HOT and Lead at Risk. Show engaged and responded. 
```
### 04 May 2020
```
- Intelligent Excel Import Beta: If your XL sheet has 1 row for each lead, try uploading your excel sheet as is. AI Assistant will try to read the data, auto format it and will let you know the identified valid leads before adding. You can check those leads and then add them.
- Now you can find out the leads uploaded from an excel file using the Excel filter in lead list. 
- Support for LinkedIn, Facebook and Twitter as source of lead.
- Fix for allowing to search by phone number with spaces in the leads list.
- Fix for mobile view email is not seen correctly when clicked in the timeline view. Especially for EmailCC source lead.
- Weekly summary email to show Engaged and Responded instead of Hot and LAR.
- Fix for Timeline view not showing the read double tick for emails "Sent as User"
```

### 29 April 2020
```
- Fix for: Multi edit - NSD shown in the row and post expanding the lead the date is not correct.  
- Fix for: Schedule table - Message Type column is too small.  
- Lead List Filters: Last 30 days, Last 1 year options added.  
- Fix for: Multi lead edit. Next Followup date. Calendar is hidden behind autocomplete suggestions from browser.  
- Excel validation for column name - user will now get the exact name of the erratic column.  
- Expanded Lead: Click to copy should be changed to Copied after clicking.  
- Filter Reset Icon changed.  
- Deselect action introduced in leads list for partially selected list.  
- Edit Assistant Signature allows use to add link to text. e.g website url linked to company name.    
- Custom Message edit/clone ability introduced in Schedules tab too.  
- Edited lead from CRM. When phone, email, name is changed then update that in 7Targets too.  
- Assistant signature in introduce me email was coming in one line. Fixed the issue.
- Fix for Context graph coming as empty many times.
```

### 23 April 2020
```
- Fixed scrollbar length for wakeup time picker (WA) per feedback.
- Changed local filters dashboard drawer styling to match leads list filters.
- Tooltip showing the daily limit of messages in dashboard today's followups widget for Sales (200) and for WA (75).
- Mobile view - leads-list - showing no. of leads, duration and criteria.
- Replaced lead source and schedule creatable select in add/edit lead with smart select common component.
- Scrollbar width increased globally.
- Fix for UI load taking more time.
```
### 22 April 2020
```
- Show the to and cc email ids from the leads response.
- Adding lead from the OOO email is an assistant level property now.
- Do not show email abuse report in timelines.
- Validate WhatsApp token 3 hrs before the wake-up time.
- Link in the quoted text in the email when assistant is copied should be retained.
- Lead At Risk email would have a Custom button for user to choose days after which user should be reminded. 
- Cold Lead with NSD earlier that today would be updated to today for WhatsApp assistant, so that no leads are dropped.
- Schedule name not appearing completely in the expanded lead. Name goes behind the button. 
- Filter look and feel changes as well filter on the left side of the screen.
- Click to copy. Let the user knows it is copied.
- Search box mouse pointer fix on the right side of the box.
- Same reset filter icon.
- Fix for WhatsApp custom message is not seen in the schedule. 
- Dont show warm and engaged icons on progress bar for unsubscribed leads.
- Fix for Multi edit. The NSD show in the row and post expanding the lead the date is not correct. 
- Login button when clicked have a loader. 
- Change youtube icon to the actual youtube icon using font-awesome.
- Schedule days is hiding behind the arrow. Increase the size to see 2 digit number.
- Fix for createDate query showing different number in list and dashboard.
- Readonly Custom message text is too light. Make it a little darker shade.
- Fix for different fonts in email body while add lead.
- Fix for Custom message name not appearing completely while selecting in the schedule if the name has no space.
```

### 17 April 2020
```
- Expanded lead to show various states of lead achieved in different followups (re-followup)
```
### 14 April 2020
```
- Warm and Engaged Filter click on dashboard to get right leads in the list. 
- Custom message from other user should not be editable and image upload should be disabled. 
- Confirmation on delete schedule and also delete button right most.
- TVL get in one line. No scroll bars for the widget. Reduce font size of the number if required. 
- Handle failures for WhatsApp notification because of concurrency. 
- Dashboard responses shows HTML characters and emojis. Lets fix this. 
- In the response forwarded email to user add space between quoted text and dividing line.
- Handle entities failure because of too long text. 
- Phone number component to be same on mobile as on desktop.
- Changed subject for whatsapp token failure notification email. 
```
### 10 April 2020
```
- Filter and Pagination in Lead List
- WhatsApp Assistant can be used for CRM Integration (Hubspot and Pipedrive)
- Phone number as one field in lead and assistant
- Show correct followup numbers (will effect from now onwards only)
```

### 07 April 2020
```
- TVL(Total Valid Leads) in Total Lead.
- Color of custom messages and schedules owned by others.
- Proper error message for add lead when user's trail is expired. 
```
### 06 April 2020
```
- Show email and phone number in the extended lead
- Continue Followup action for Hot and Responded leads
- Daily WhatsApp summary report email subject change
- Defect fix for Schedule name dropdown icon not working
- Don't use old user_typed_message when restarted
```
### 04 April 2020
```
- Fix for multi lead restart from UI.
- Fix for Whatsapp to pick the right contact incase multiple found while searching in WhatsApp
```
### 02 April 2020
```
- Fix for multi lead assignment from Hubspot.
- Hubspot integration is ready to go public.
```

### 01 April 2020
```
- Defect of excel error when login to email assistant from whatsapp.  
- Ignore Invalid Email and Invalid WhatsApp Numbers in the % calculation in dashboard.  
- Show schedule name for the lead in the lead list.  
- Ability to search the schedule in add/edit lead.  
- Excel Validation fix for CHAR 160.  
```

### 31 March 2020
```
- Ability to clone custom message.  
- Default dashboard to Quarter.  
- Leads NSD is old (less than today) , send the list of those leads to support.
- Image view ability in Add Lead Multiple (WA) and Image preview ability in single lead (WA) for existing images in custom messages.  
- Custom Message to be seen properly on timeline view.  
- Ability to see the image on timeline view for WhatsApp.  
- Date tool-tip shown in carousal can be just below the numbers to avoid hiding the numbers.  
- Carousal for multi-add lead for sales and WhatsApp both.   
- "Restart Followup" button should not come for Unsubscribed lead.
- Day Summary run for WhatsApp Assistant on support group.  
```

### 28 March 2020
```
- Schedule with custom message for WhatsApp Assistant too. Image in custom message is possible. 
```
### 26 March 2020
```
- Show correct images in timeline view as per what is uploaded while adding lead.
- SendLeadResponseTo available in mobile Assistant Edit too.  
- Defect: Schedule with custom messages owned by admin to be visible to all users.  
- Defect: Schedule and Custom Message Soft Delete.   
- Defect: Messages seen in timeline is not aligning with schedule when used Candid in followup_2 or later.  
- Defect: Do not show the warning to Subscribe to user if he has active plan and just trying to change the plan
- Defect : WhatApp Edit lead at times schedule comes empty.  
```

### 25 March 2020
```
- One Assistant per day will not send more than 200 emails. Emails beyond 200 for that day will be pushed out by 24 hrs.  
- WhatsApp Assistant, retry after failure because of no internet while trying to use WhatsApp.  
- View Email button in the Lead at risk email sent to the user. 
```

### 24 March 2020
```
- Correction in dashboard graph to query based on update_date to get aligning data with the counts.  
- Show counts in pie chart tool tip.  
- Carousal in Multi Add Lead.  
- Domain correction for Email address verifier.  
```

### 23 March 2020
```
- Responded lead count in dashboard with proper ordering of counts too.  
- Ability to mark a lead Responded from the UI.  
- Pipedrive marketplace ready App for it to be publicly available.  
- Edit Lead to show message as per schedule.  
- Multi-lead edit, fix the modal view for usability.  
```

### 20 March 2020
```
- Link to get to the lead details from the response email sent to the user.
- Ability to edit multiple leads from the UI.  
- Ability to filter the State graph in Dashboard on various different context. As well the Context graph on various different status values.
- Ability to send the received response from lead to configured email ids. So that the response can be sent to more than user for quick action. 
- Dashboard to show %ages too along with the exact numbers. 
```
### 17 March 2020
```
- Ignore/Trim Space in WhatsApp and email while add and edit lead. So that Duplicate leads are avoided. 
- Don't allow duplicate leads based on email for same user.
- Don't show the bounce emails in "Lead Response" on Dashboard. 
- Show Email id too in the LAR email to user to be able to clearly identify who is the lead.  
- Process not more than 75 leads per day for WhatsApp Assistant.  
- On unsubscribe and deactivate action close the modal window. 
- Bullet option in custom message editor
- Remove non-unicode in create and edit custom message. So that when user pastes from google doc it does not fail.
- Ability for user to edit the Assistant's email, specifically login part. So that user can align it to their company standards. Default is still the assistant's name.
- Improve Add Lead button in mobile view so that pagination is accessible.  
- Fix the issue where schedule is not seen at times in add and edit lead. 
```

### 12 March 2020
```
- PS: Nurturing line should always be on a new line in the email.   
- Checkbox for selecting an expanded lead in the lead list.  
- IntroduceMe popup. Scrolling issue on desktop.
- Space in the email at the end while login(email id) gives wrong credentials. Spaces in the end are trimmed.  
- Timeline view horizontal scrolling buttons for usability.  
- Notes were not getting saved for Deactivate and Unsubscribe actions.  
- For IE and other browsers show. "This browser is not supported. Please switch to Google Chrome or Mozilla Firefox for best results."  
- Buttons for timelines view edit message popups to be visible on mobile when user types.  
- WhatsApp multiple leads. The email does not reflect/change as per the schedule changed. 
- Carousal while Add lead for WhatsApp. Single lead only for now.
- Multiple usability fixes.  
- Tooltip for Clone, to help understand what it does.  
- For WhatsApp expanded lead in lead list, show the phone number instead of email.  
- Ability to add CC email in Introduce Me. So that user can copy some other Sales individuals to introduce them.
- Stability fixes for WhatsApp assistant processing. 
- Ability to send image on any of the scheduled messages in WhatsApp for UserTypedMessage
- Notify support if 7Targets is not able to notify engaged lead on WhatsApp.
- Failures on WhatsApp are specifically notified to support
```

### 04 March 2020
```
- Custom Message now has a better UI to write email where you can bullet the points, use color and links (href), etc.
- Pending Review emails will be automatically checked for deliverability and action taken (deactivate on bounce or send the email on confirmation) automatically.
- See the default schedule in the list of schedules. 
- Set the schedule to default while creating or editing it from the schedule page itself.
```

### 22 Feb 2020
```
- Native Integration for Pipedrive. Can now be in Pipedrive Marketplace.
- Edit Assistant - Functional Grouping of attributes for usability
- In multiple leads upload, show excel errors straight away on excel upload, not on click of add lead.
- Change the schedules & custom message to  more usable. 
```

### 19 Feb 2020
```
- Tour for Add Lead
- Bigger font and in same line for Book Meeting and  WhatsApp link
- Nurturing statement. PS is bold and all the text is italics. 
- Introduce Me simplification.
```
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
