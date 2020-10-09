---
date: 2020-01-13
title: Lead Responses
description: Lead Responses
type: Document
sidebar:
  - {id: lead-responses), text: Lead Responses}
  - {id: lead-state, text: Lead State}
  - {id: questions-answered, text: Questions answered}
categories:
  - assigning-leads
---

<a name="lead-responses"/>
## [Lead Responses](#lead-responses)
Emails responses are read by the Assistant and would try and decide the email intent.  

The machine learning model/s tries to identify if the response conveys an 
- out of office or 
- asks to stops sending any further emails or 
- agrees to have a meeting at a particular day or
- requests for brochure  
 
helping the assistant take right action and update the lead state.

## [Lead State](#lead-state)
Assistant will categorize the leads in various states based on the followups and responses. Various possible state are:   
`Hot` if the lead has accepted to meet.   
`Cold` the followup is under progress.   
`Warm` lead is someone who has opened 3 or more emails. A good list for your calling team to call.  
`Engaged` lead is someone who has opened 1 or more emails.  
`Processed` followup is completed as per the schedule and there was no response from the lead.    
`Out of office` received an out of office from the lead. Assistant will restart the followup after lead returns back to office.  
`Deactivated` lead responded back asking to stop sending emails. Lead email id is invalid as verified by the assistant. Email sent to the lead bounced. 
`Unsubscribed` lead used the unsubscribed link in the email or responded asking to unsubscribe.   
`Responded` state for the lead conveys that there is some response from the lead and Assistant was not able to categorize it to one of the above.  
`Pending` means Assistant is still validating the email address of the lead.  
`New` conveys that the lead added cannot be processed as you have used up your leads limit as per the plan. You can Restart these leads in the next period or upgrade your plan and then restart these leads now.  

## Questions answered
- Why some leads are showing as Pending ?
- Why some leads are showing as New ?
- Why some leads are showing Deactivated ?
