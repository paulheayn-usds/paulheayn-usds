# Questions for Eric
## Goals

*What is SSA's primary goal with improving the office locator?*

Eric explained the office was the last step in  the service funnel and we should attempt to help the users be as efficient as possible.
> Get users to office as quickly as possible. we've done our best with the website. Service strategy is web then phone then office. thats is our preference from business preference. In general drive people to online service.

> Look at bigger picture of service funnel and its just one step in a larger process.

Eric also explained that searching by zip code might not be the most efficient way, especially in larger zip codes.
> There are lots of offices, identified location from zip code, but its not the best way to identify closest office especially not in larger zip codes. Ideally, we include mapping, the locations themselves, address and basic information but certain service attributes and wait times

Another thing we should consider is how we think about usage of the office locator. Eric mentioned the following statement which means we should extend our thinking from a standalone web page users come to to get location data to an integrated service part of a larger experience like setting up an appointment.
> If I'm a user and I want to apply but not use self-service, I need to schedule interview and identifying location is part of that process. Office locator could stand alone or it could be injected in the pack of service

## Scope

*Should we only focus on accessible data via ROOMS? Or plan to integrate third-party APIs (mapbox, city public data)?*

When we talked about the use case, Eric dove into the differences in field offices. Stating we should attempt to utilize the DOORS data and merge data from other third party APIs to create a new experience
>Not offices are created equally - some in city with no free parking, others with it. self-help PCs, not all offices have that. DOORS will have this information

> No limitations on API usage - DOORS data will join up with other data on flat file so anyone can ingest it. DOORS api can only be called by zip code. you'd have to find all adjustent offices. If we can export it all to flat file we can export it all to app and not worry about api calls.

> We can use third-party APIs but need to be mindful of contracts - when we start paying, we have to have a contract and need companies to compete for it and it slows down progress.

> If the [map] data is open source we can pull down to reference on our own

Finally, we want to consider the cost benefit of using internal tools. We have access to some powerful tools, but if the end user can't use the map, its not worth the extra features.
> There is arcGIS data which we have access to it, but we want consumer friendly mapping

*What is out of scope?*

For the concept we shouldn't limit ourselves as much, the data we have access to will do that for us.
> DOORS can add attributes. In time scale, we can have some in there, but office wait time is a wish list item.

*How do we handle content controls for field offices, such as field office closures for inclement weather?*

We could include content controls for field offices in concepts, but that functionality isn't yet built.
> There will be temporary controls but its not available now. Data in this feature will probably message and expectation for reopen, but its not being worked on right now.


```
Action Item
Paul to follow up with Tom Nielsen on the work he has done with the Justice 40 team and understand the free federal mapping tool they are using.
```

## Users and Stakeholders

*Which field offices might be the best to talk directly with users?*
We have some data from regional offices, but we need to get in front of users and talk with them.
> I've been working with regions to get information on them to understand types of information. But we've been relying on customer feedback through agents, need to talk with customer


```
Action Items
Paul will follow up with Sylvie to gather data Eric collected while talking with regional offices
```

## Usage Data and Background Information ##

*Is all field office capabilities in the DOORS system?*

Most offices are similar in functionality with a few outliers. But Eric much of this data will be added to DOORS in the future
> There is a standard list of service offerings per office - parking, self-help pcs.
> All are full service with very few exceptions for card centers (nyc and philly only focusing on cards and name change services)

*Do we know, on average, how many people come into the field offices?*

We have visitor data from internal systems, but the data isn't uniform

> We have the  ZIPPER visitor intake. It contains wait times, but can't use that its not apples to apples - offices cue people differently. Some offices use a two stage cues where the first cue is for quick assessment and the second cue doesn't show in MI. This leaves some field offices to have wait times of 2 minutes, while in other field offices you get a ticket and wait 40 minutes until you get an agent.

*How will the office change post-pandemic?*

Eric dove deep into how the office will change and what some of the problems field offices are facing right now.

> We want to use the office to help those who need it the most and have the most complicated tasks. For everyone else they should use the self-service channels. We want to prioritize.

> We can't stop people from just walking in, we will always have to be full services. We are trying to make the check-in process more consistent with consistently measured wait times.

> In the new model, we are doing away with check-in kiosks. Our check in today, you type in your SSN, reason for business, if you have an appointment or not. We found some of our customers are very slow if they don't remember SSN or spend a lot of time selecting the correct service.

> This causes bottlenecks at the start of the day when there is a huge influx and the managers come around and enter in the information for them - the manager can do it faster and can move people in larger status.

> This rush in the morning means the models failed.

SSA plans on removing the kiosk and will use agents to walk around and help customers while in line.
> In the future we are removing the kiosk from station and will have an agent and will do the wayfinding, assessing need.

> The experience will change but service won't

This led to conversation about the SSA mobile app that was in development, but he wasn't sure of the project status

> We have a mobile check-in app that we were building out, where a customer can bring an app up and identify service location and pre-check into their appointment. I'm not sure what the status is right now or how it will integrate with it?

Andy and his shop worked on the mobile app so we can reach out to him to understand more

*Do we have access to web analytics for the office locator?*

Yes, we do. It's in MI and tagged in Google Analytics.

>In the last year office locator average 1-1.4M/month unique visitors a month or about 14M a year. It looks like it was going down and then spiked - back in 2011 it was 12-13M for the year, then started dropping 2019 it was down to 9M for the year.

Analytics data from MI matches with Google Analytics, at least visitor-wise
> MI shows 1.19M Unique and on Google Analytics its 1.2M unique, average time on page is 1m35s, 30% of customers exit from there
> In Google Analytics, search for folo - three tags, ifolo/officesearchandresults, otheragenciesinyourarea + error pages (?)

There is this additional feature where the office locator links to other community service phone number
> The existing office locator has a feature that brings up other agencies with community service phone numbers, but it was never discussed if it gets used or why
> We shouldn't look only at generalized web data since it won't answer why - it should be tested
> According to Google Analytics, 'Other agencies' link is used by 2% of customers average time on page is 4 minutes and 3 seconds


```
Action Item
* Ping Eric.Christiansen@ssa.gov to get numbers on field office visits from ZIPPER visitor intake system
* Email Sylvie about the Mobile app and get in touch with Julius
* Talk to Andy about the mobile app
* Email Sylvie to connect with Elizabeth Hanover since she has been working on the office information effort. She is an area manager in the Boston region and might have more perspective from a different level.
```


# Raw Notes (unedited)

## Scope
  * How do field offices handle content controls (office closing, hours, wait times?)?
  * Focus on accessible data via ROOMS? Or plan to integrate third-party APIs (mapbox, city public data)
  * What is out of scope?
## Stakeholders
  * How can I talk with local offices?
  * Which field offices might be the best to talk directly with users?
  * Who else do you recommend I talk with?
## Strategy
  * Initial qualitative feedback on prototype
  * Build design MVP and user test it with users
  * Adjust feedback
## Data
  * Do we have access to field office usage data?
  * How has the field office usage changed since the pandemic?  
  * Do we have access to analytics for the current office locator?
  * Do you have any studies or data conducted with the field office to understand what is needed from their end in an office profile?
  * On average, how much foot traffic does a field office bring in (pre-covid)?


## Answers
* Goals - What the customer wants - business- lots of offices, identified location from zip code, but its not the best way to identify closest office especially not in larger zip codes. ideally include mapping, locations themselves, we need to show address and basic information but certain service attributes and wait times
* Get users to office as quickly as possible. we've done our best with the website. Service strategy is web then phone then office. thats is our preference from business preference. In general drive people to online service
* We live in a time where people don't go to offices. eventually we'll go back to an office. if you are going to the office to get benefits, you will want to set an appointment.
* Look at bigger picture of service funnel and its just one step in a larger process.
* I want to apply but not self-service, i need to schedule interview - identifying location is part of that process. office locator could stand alone or it could be injected in the pack of service
* Not offices are created equally - some in city with no free parking, others with it. self-help PCs, not all offices have that. DOORS will have this information
* MVP will not have all items. Working with regions to get information on them to understand types of information
* Relying on customer feedback through agents, need to talk with customer
* Having a concept is more efficient than handing something
* DOORS can add attributes. In time scale, we can have some in there, but office wait time is a wish list item.
* User looking for office near me - it shows me wait time at a glance because it informs decision on which to pick.
* Talk to slyvie on regional offices
* Working on content controls - temporary controls but its not available now, with message and expectation for reopen
* Existing office locator has weird features - brings up other agencies with community service phone numbers - never discussed if it gets used or why
* Generalized web data but won't answer why - it should be tested
* We have details from the field in CBO - the office - can use them to be interviewed. Michelle and Ashley
* No one is going to field office - go to recruitment of someone who has used the office service channel - 'have you been to an office for an interview or other service need?'

* Data point - standard list of service offerings per office - parking, self-help pcs.  - all are full service, very few exceptions for card centers (nyc and philly only focusing on cards and name services)
* Have ZIPPER visitor intake - has wait times, but can't use that its not apples to apples - offices cue people differently - two stage cues - tick you and pull you in for quick assessment - second cue doesn't show in MI in other places you get a ticket and wait until you get an agent.
* Ping Eric.Christiansen@ssa.gov to get numbers on field office visits

* Change in office? Use the office to help people who need it the most and the most complicated. for everyone else use the self-service channels. We want to prioritize. We can't stop people from just walking in, we will always have to be full services. we are trying to make checkin process more consistent with consistently measured wait times. in the new model, we are doing away with check in kiosks. Our check in today, you indicate SSN, reason for business, if you have an appointment or not. We found our customers are very slow if they don't remember ssn or spend a lot of time selecting the correct service.
  * When offices open, there is a huge influx and do it for them, the manager can do it faster and can move people in larger status. rush in the morning means the models failed. removing kiosk from station and will have an agent and will do the way finding, assessing need. the experience in office will change and reopen
  * Experience will change but service won't
  * Mobile check in app that we were building out, where a customer can bring app up and identify service location and pre-check. im not sure what the status is right now or how it will integrate with it?
  * Email Sylvie about mobile app - Julius

* No limitations on API usage - DOORS data will join up with other data on flat file so anyone can ingest it. DOORS api can only be called by zip code. you'd have to find all adjustent offices. If we can export it all to flat file we can export it all to app and not worry about api calls.
* We can use apis but need to be mindful of contracts -
* There is arcGIS data which we have access to it, but we want consumer friendly mapping
* Google maps has usage limitations - when we start paying, we have to have a contract and need to compete for it.
* If open osurce data we can pull down to reference on our own
* Tom Nieslen, for justice 40 team,  for deep dive of mapping (federal tool that is free)

* Traffic - in last year field office average 1-1.4M/month. looks like it was going down and then spiked - back in 2011 it was 12-13M for the year, then started dropping 2019 it was down to 9M for the year
* Get to MI for secure apps. 1.19M Unique, on google its 1.2M unique, average time on page is 1m35s, 30% of customers exit from there
* 'Other agencies' link is used by 2% of customers average time on page is 4 minutes and 3 seconds
* On average probably searching 2 zip codes
* Search for folo - three tags, ifolo/officesearchandresults, otheragenciesinyourarea + error pages (?)
* Traffic is tagged and might be in google analytics
* Elisabeth Hanover - silvie can connect with her. she has been working on the office information effort. she is area manager in boston region. she might have more perspective from different level
*
