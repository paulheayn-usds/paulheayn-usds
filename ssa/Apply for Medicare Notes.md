# Applying for Medicare Process

### Business Logic
Turn 65 >> Enroll in Plan A during enrollment period for hospital visits

## Actions
* Apply for Plan A and Plan B
* Return to saved application
* Check status
* Replace medicare card
* Checklist for application

## Out of Scope (??)
* Manage benefits

### Eligibility to apply
* Initial enrollment 3 months before you turn 65 to 3 months after you turn 65
* Can enroll in Plan B, but monthly premium will go up 10% for each 12-month period you skipped
* Can enroll every year from Jan 1 - March 31st
* Can enroll outside enrollment window if you are working after age 65 *and* covered under another group health plan. Then you _may_ qualify for a Special Enrollment Period (SEP)
* Coverage starts July 1 of the year you enroll

### Special Enrollment Period (SEP)
* Need to be eligible (working and covered)
* Can sign up for Plan B any time you are working and covered
* Can sign up for Plan B 8 months after you stop working or stop being insured
* *Edge case* If you stop working or stop covered during the initial enrollment period, you *do not* qualify for a SEP
* Can sign up if job ended in the last eight months but still maintain coverage through severance or retirement pay (_Note: Not sure what this means exactly_)
* *Edge case* COBRA and retiree health plans aren't considered coverage based on current employment and not eligible for SEP


## Edge cases
* Puerto Rico residents need to register for Plan B
* If disabled and 65, you are automatically enrolled in Plan A & Plan B

## Types of Medicare
### Part A
* eligible if older than 65 and paid enough Medicare taxes
* in-patient care like a hospital visit

### Part B
* Requires monthly premium
* Service oriented like doctor visits

### Supplemental
* bridging gap between plans like co-payments, co-insurance, and deductible expenses

### Medicare Advantage Plan
* Plan A & B & Additional coverage like prescriptions, vision, hearing, and dental
### Part D
* Covers prescription drugs

## Website
Four sections to the website
1. Medicare Only application
2. Medicare Plan A & B Eligibility
3. Medicare Plan D Assistance Application
4. Medicare Adjustment Request

### Medicare Plan A & B Eligibility
https://app.mural.co/invitation/mural/usdigitalservice0135/1631033874570?sender=u07f6bf104eabaebba0153991&key=5df71616-3a77-40db-8129-0a8d9af77668

### Medicare Adjustment Request
*Seems like there is legislation requiring document verification for much of this process*
* Needs new initial determination
* Beneficiary ore representative payee can file
* Must be eligible for Plan B & Plan D

#### Users
* Initial Medicare Eligibility
* Life changing event

#### Current Limitations
* Can't submit initial determination online (why not?)
* If life event, needs to fill out this form: https://www.ssa.gov/forms/ssa-44-ext.pdf
* Copies of SSA44 require documents mailed or in-person :(
* Can only be done via phone, in-person, or mail
* Identification can't be completed via phone - could login.gov work here?

#### Current Systems Functionality
* Only access by specific employee level
* Data collection - gathering or updating documents, maybe
* Querying - search with filters or data processing
* Calculator - check adjusted Income-Related Monthly Adjustment Amount (IRMAA) | no save function

#### Initial Assessment
*Most Amount of work*
* Utilize login.gov for authentication, online scanning of documents and let them fill out the SSA44 form online - follow up with an appointment for clarification

*Middle ground*
* Move SSA44 document online with the ability to set an appointment

*Least Amount of work*  
Add an eligibility checker so if a user can determine if they would qualify for a new initial determination
