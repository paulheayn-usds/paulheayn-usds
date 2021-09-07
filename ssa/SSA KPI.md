## KPIs across Service Channels
We are trying to understand how the user interacts with the site and if they can complete the transactions we are building online.

At the moment, we can't track across all service channels and we might not want to since that would require a much larger engagement. We will have an incomplete view of the users' experience, but we should create KPIs that try to understand how the website is performing for them.


## SSA Website Redesign Goals
We want people coming to the new beta site and starting an eligibility check or an application - either would be qualified as activation of a user for the unauthenticated experience.

As a secondary goal, we should measure satisfaction via Medallia. But should be more specific about what 'satisfied' means. Does it mean happy with result? Easy to use? Easy to find the information? Quick? Thorough?

These goals can be broken down into three questions:

1. Are users opting to use the new beta.ssa.gov site over the old ssa.gov site?
2. Are users completing customer transactions more?
3. Are users more satisfied with the result?

## How can we measure goal success?
There are a few frameworks we could use to measure success, but most are built with commerce or revenue-generation in mind. Instead of taking these frameworks in its entirety, we should pare down the areas of focus. The two frameworks focused on here are the Pirate Metrics and the HEART framework.

Pirates Metrics is extremely focused on revenue generation and won't be examined in this portion, but there is a section in the Appendix to learn more about the framework.

The site metrics will utilize the HEART framework to help set goals, signals and metrics.

### HEART
Google created the HEART framework which takes into consideration different dimensions on product usage. We won't be able capture the true user experience with the various different service channels (phone, web, in-person). However, this framework would be good to help us try to determine what is useful for us.

HEART stands for:

* Happiness - satisfaction, perceived ease of use, net promoter score [[2](#2)]
* Engagement - frequency, depth of interaction over time period [[2](#2)]
* Adoption - new users of product
* Retention - return rate in a time period, churn rate
* Task Success - time to complete task, percent of task completed, error rate

| | Goals | Signals | Metrics |
|---|---|---|---|
| Happiness |Increase user satisfaction with the site | Number of users going to beta.ssa.gov; Number of users filling out the Medallia survey| Percent of total ssa.gov traffic going to beta.ssa.gov; Percent of ssa.gov traffic filling out survey; Design Satisfaction Average Rating; High Design Satisfaction (4 or 5) to Low Design Satisfaction (1 or 2) Ratio; Comprehension Satisfaction Average Rating; High Comprehension to Low Comprehension Ratio; Navigation Satisfaction Average Rating; High Navigation Satisfaction to Low Navigation Satisfaction; Sum of all High Satisfaction Scores to Sum of all Low Satisfaction Scores Ratio|
| Engagement | Increase the number of applications started | Accounts created; Percent of monthly users who log in; Page views on 'start application' page; Time spent on site; Number of pages viewed per session; | Percent of users starting an application; Average time on site; Average time on site for users who completed an eligibility check;  |
| Adoption | Increase the number of users checking eligibility| Number of users going to beta.ssa.gov; Number of users taking no action after checking eligibility;  | Percent of total traffic going to beta.ssa.gov; Percent of beta.ssa.gov users starting eligibility check; Eligibility check completion rate; Average time spent on eligibility check; Post-eligibility check exit rate | |
| Retention | Increase the number of users who come back to the beta.ssa.gov site with in x weeks| Churn rate; Bounce rate; 30D new user retention; | 30D new user retention; beta.ssa.gov exit rate; Monthly Churn Rate; |
| Task Success | Increase the number of users who successfully complete an application[*](app) | Number of users who did not finish an application; Time spent to complete an application  | Average time to complete an application; Application completion rate; |

\*<a name="app"></a>_Application is used as a generalized catch all for eligibility check, benefits application, disability application._

## Possible Metrics to follow
* Percent of total ssa.gov traffic going to beta.ssa.gov
* Percent of ssa.gov traffic filling out survey
* Design Satisfaction Average Rating
* High Design Satisfaction (4 or 5) to Low Design Satisfaction (1 or 2) Ratio
* Comprehension Satisfaction Average Rating
* High Comprehension to Low Comprehension Ratio
* Navigation Satisfaction Average Rating
* High Navigation Satisfaction to Low Navigation Satisfaction
* Sum of all High Satisfaction Scores to Sum of all Low Satisfaction Scores Ratio
* Percent of users starting an application
* Average time on site
* Average time on site for users who completed an eligibility check
* Percent of total traffic going to beta.ssa.gov
* Percent of beta.ssa.gov users starting eligibility check
* Eligibility check completion rate
* Average time spent on eligibility check
* Post-eligibility check exit rate
* 30D new user retention
* beta.ssa.gov exit rate
* Monthly Churn Rate
* Average time to complete an application
* Application completion rate

## Prioritizing 5 Metrics
1. Application completion rate
2. Sum of all High Satisfaction Scores to Sum of all Low Satisfaction Scores Ratio
3. Eligibility check completion rate
4. Average time to complete an application
5. Percent of total ssa.gov traffic going to beta.ssa.gov

Above, retention metrics are deprioritized at this time to focus on increasing user eligibility checks and applications. Eventually, SSA should monitor retention and try to improve this metric, but its not necessary at this stage.

### Prioritizing Application Completion Rate
Application completion rate is prioritized due to the interdependencies this metric has on other aspects of the site. If eligibility check rate is improved, it could lead to more traffic entering into the application funnel. High satisfaction could be due to ease of discovery of the application and the process.

### Is Application Completion Rate a good proxy for product success?
Success rate could be effected by factors out of our control:
* Authentication not working
* The logged in experience not as helpful
* Finishing the application by phone or in-person

However, these issues are a constant and we can see how users take the information provided to them in the unauthenticated space and get them through the application process.

### How could Application Completion Rate Be Gamed to fake success?
* Decrease the number of users entering the application funnel
* Change criteria for application completion (e.g. mark users who reach 'mail in materials' step as complete)


## Next Steps
1. Get input from the USDS team
2. Get input from SSA

## Appendix

### Pirate Metrics
Pirate metrics are revenue-focused, where the goal of the product is to retain users to extract value later.
* Acquisition
* Activation
* Retention
* Revenue
* Referral

#### Acquisition
Do we care about acquisition? The government doesn't purchase traffic, but organic traffic sources would allow more optimized SEO. However, this is outside the scope for the initial redesign and therefore we should skip this

*Verdict*: Skip

#### Activation
Depending on the life phase a user is going through, activation could be as simple as downloading information to start research. But that doesn't really let us know that someone is interested in social security services.

Instead, maybe we should consider activation as someone who wants to do more than read and they want to understand if they are eligible for a service. However, not every visitor will start at the eligibility stage, so we should consider how we separate new users and existing users.

*Verdict*: Most likely needed - more discussion needed

#### Retention
Most product teams watch retention when the problem has a natural occurrence in daily, weekly or monthly timeframes. I am not sure how often someone needs to apply, check status, or submit an appeal, but I don't think there is a regular frequency for these actions.

*Verdict*: Not needed right now, but should track

#### Revenue
While SSA doesn't generate revenue, keeping users from tying up technicians could be tracked as a cost savings. This seems a lot more complicated and probably not necessary.

*Verdict*: Skip, but maybe come back later if more complex data is needed

#### Referral
Similar to Acquisition, SSA most likely doesn't need to know how much word of mouth the website is generating. SSA.gov is there for citizens to receive a service and is the only solution.

*Verdict*: Skip


## Source(s):
* <a name="1"></a>[1] https://www.interaction-design.org/literature/article/google-s-heart-framework-for-measuring-ux
* <a name="2"></a>[2] https://library.gv.com/how-to-choose-the-right-ux-metrics-for-your-product-5f46359ab5be
