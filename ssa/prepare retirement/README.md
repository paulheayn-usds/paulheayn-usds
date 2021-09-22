# <a name="top"></a>Contents
* [Summary](#summary)
* [Out of Scope](#outOfScope)
* [Prepare for Retirement](#prepare)
  * [How it works](#howItWorks)
  * [Eligibility](#eligibility)
  * [Starting Benefits](#startingBenefits)
  * [Edge Cases](#edgeCases)
  * [Pensions and Windfalls](#pensionsAndWindfalls)
* [Calculator](#calculator)
  * [Benefits for Spouses](#spouseBeneCalc)
  * [Government Pension Offset Calculator](#gpoCalc)
  * [Late or Early Retirement](#lateOrEarlyCalc)
  * [Life Exceptancy Calculator](#expectancyCalc)
  * [Online Benefits Calculator](#beneCalc)
  * [Quick Calculator](#quickCalc)
  * [Retirement Age Calculator](#ageCalc)
  * [Retirement Earnings Test Calculator](#earningsTestCalc)
  * [SSA Benefit Eligibility Screening Tool](#bestCalc)
  * [Windfall Elimination Provision](#windfallCalc)
* [To Do](#todo)


# <a name="summary"></a>Summary
The current landing page has an explanation of how it works and eligibility and when you can retire. Its a lot of text and I think a lot of the text could be paired down or converted into explanatory images/infographics

It gets tricky when the page starts to talk about edge cases - military, farm work, self-employed, etc. There might be a small number of people who fit multiple cases, but I think for the majority of the users, we could show contextual information.

The next section talks about pensions, which aren't too complicated to understand, but Windfall Elimination Provision is pretty complicated - I still have no unpacked this portion. Again, we might not need to show this information if it is not pertinent to the user.

# Questions to Answer
* Do we want to continue to support multiple calculators to allow users to get the information they need quickly?
* How many times does a user come back and reuse a calculator?
* Could we add functionality to save the results or email the results so they don't have to do the calculator again?


# <a name="outOfScope"></a>Out of Scope
* [Retirement Estimator](https://www.ssa.gov/benefits/retirement/estimator.html) - This requires authentication
* [Detailed Calculator](https://www.ssa.gov/OACT/anypia/anypia.html0) - It might not be out of scope, but I don't have enough time to dive into the calculator right now. We should follow up and see if we need to port this and add it to the backlog

[back to top](#top)

# <a name="prepare"></a>Prepare for Retirement

## <a name="howItWorks"></a>How it works
* Who gets it - older people, disabled people, survivors, dependents of beneficiaries
* Future generation pays for your SSA when you retire
* On average, 40% of retirement comes from

## <a name="eligibility"></a>Eligibility
* Based on a credit system, need 40 credits to qualify
* 40 credits usually equals 10 years of work
* Earning more credits doesn't equal more benefits - credits are used for *eligibility only*

## <a name="startingBenefits"></a>Starting benefits
* Early retirement - starts at 62, but reduce benefits
* Full retirement - starts at 66 (1943-1954) and increases gradually to people who were born in 1960 where retirement is 67
* Delayed Retirement - Benefit increases until age 70
* You can continue to work while receiving benefits, earnings will delay benefits

[back to top](#top)

## <a name="edgeCases"></a>Edge Cases
**[Farm](https://www.ssa.gov/benefits/retirement/planner/farmwork.html)**
* Boss must report to SSA how much they paid employee so employee can get credit for work
* $150 or more in cash per calendar year should be reported
* Paid less than $150 in cash, but employer agricultural labor is $2,500 or more for the calendar year
* Seasonal workers qualify if commute to work daily, paid on piece-rate basis, employed less than 13 weeks in the last year, and paid at least $150
**[Federal Workers](https://www.ssa.gov/benefits/retirement/planner/fedgovees.html)**
* Gov't employees from 1983 or earlier didn't pay social security and were on the Civil Service Retirement System(CSRS), which provided retirement
* If you stay on CSRS you can't get Social Security retirement benefits but you are covered under medicare

**[Military](https://www.ssa.gov/benefits/retirement/planner/veterans.html)**
* Can get both military retirement and social security benefits
* If served between 1940 and 1956, no social security tax was paid, but can get a 'special earning' to help qualify
* Active duty between 1957 and 2001 can be credited to social security earnings record
* No extra earning credits for military service after 2001
* Active Duty for the following:
  * Air Force
  * Army
  * Coast Guard
  * Coast & Geodetic Survey (CGS)
  * Marines
  * National Guard
  * Navy
  * Commissioned Officer in the Public Health Service (PHS)

**[Non-profit Employees](https://www.ssa.gov/benefits/retirement/planner/religious.html)**
* If you earned more than $100 from a nonprofit or religious org, you have to pay social security taxes
* Some religious groups do not have to pay the tax and will not participate in social security benefits or medicare (amish and memonite) [[source](https://www.ssa.gov/OP_Home/handbook/handbook.11/handbook-1128.html)]

**[Railroad Earnings](https://www.ssa.gov/benefits/retirement/planner/railroad.html)**
* Railroad (RR) workers receive a pension
* Railroad Retirement Board keeps track of Earnings
* If worked in RR industry for less than 10 years and have less than 5 years of RR earnings after 1995, railroad earnings will be counted in social security credits
* If 10 or more years in RR and 5 or more years after 1995, you could qualify for a Railroad pension and RR earnings won't be calculated for determining social security credits

**[Self-Employed](https://www.ssa.gov/benefits/retirement/planner/netearns.html)**
* Net earnings need to be reported to SSA and IRS
  * Net Earnings = (Gross Earnings) -  ((Business Deductions) + (Business Depreciation))
* Net earnings does not include:
  * Dividends
  * Loan Interest
  * Real estate rentals, unless you're a relator
  * Income from limited partnership
* Must file taxes if Net Earnings is $400 or more
  * Form 1040
  * Schedule C or Schedule F
  * Schedule SE
* If you don't owe income tax, you must still pay self-employment social security tax.

**[State/Local Government Employee](https://www.ssa.gov/benefits/retirement/planner/stateandlocal.html)**
* If covered by state/local pension & social security, you pay social security and medicare taxes
* If only covered by state/local plan, you don't pay social security taxes

**[Work Outside the US](https://www.ssa.gov/benefits/retirement/planner/international.html)**
* US has international agreements with a number of countries so you don't have to pay social security to both countries
* US can count work in other countries for social security credits
* Work credits from the other country stay on record in that country and could allow you to qualify for a separate benefits

[back to top](#top)

## <a name="pensionsAndWindfalls"></a>Pensions and Windfalls
**[Windfall Elimination Provision(WEP)](https://www.ssa.gov/benefits/retirement/planner/wep.html)**
* If you receive a pension outside of social security, it could reduce the social security benefit

[back to top](#top)

# Come back later for help???
```
 Need help in this area
```

**[Government Pension Offset](https://www.ssa.gov/benefits/retirement/planner/gpo-calc.html)**
* Are you a widow of a federal, state, or local government employee receiving a pension? If so, it could reduce your social security benefits
* If you received one of these pensions and didn't pay social security tax, your spouse's social security benefit will be reduced by 2/3 of the amount of your government pension
* Doesn't apply if:
  * Pension isn't based on Earnings
  * If you paid social security taxes and you filed/were entitled to spouse/widow benefits before 4/1/2004; last day was before 7/1/2004; paid social security taxes on earnings from the last 60 months
* Edge cases on not reducing social security spouse benefits
  * Switched from CSRS to FERS after 12/31/1987
  * Received government pension before Dec 1982 and met all requires for Social Security spouse benefits in effect January 1977
  Received federal, state, local government pension before 7/1/1983 and were receiving 1/2 support from spouse

[back to top](#top)

## <a name="calculators"></a>Calculators
### <a name="spouseBeneCalc"></a>[Benefits for Spouses](https://www.ssa.gov/OACT/quickcalc/spouse.html)

[https://www.ssa.gov/OACT/quickcalc/spouse.html](https://www.ssa.gov/OACT/quickcalc/spouse.html)

**Takeaways**
* UX
  * Fields are too small
  * No main call to action
  * calculator hidden on the page
* Tons of explanatory text that could most likely be explained differently or before a user gets to the calculator

**Next Steps**
* I have no idea how often this gets used
* I also am not sure if this should be an ad-hoc calculator or integrated into a larger calculator

![Benefits for Spouse](images/benefitsForSpouseResults.png)

[back to top](#top)

***

### <a name="gpoCalc"></a>[Government Pension Offset Calculator](https://www.ssa.gov/benefits/retirement/planner/gpo-calc.html)

[https://www.ssa.gov/benefits/retirement/planner/gpo-calc.html](https://www.ssa.gov/benefits/retirement/planner/gpo-calc.html)

**Takeaways**
* UX
  * Calculator is below the fold
  * Doesn't define what 'today's dollars' is
* Tons of extra information
  * Intro text
  * Why you might be exempt (ask the user and only show them if they need it!)
  * Documentation you'll need and explanations on what certain inputs will do to your benefit

**Next Steps**
* Again, we don't have metrics on this
* Seems like it could be useful as an ad hoc calculator if a user is trying to understand implications of their government pension

![GPO Calculator](images/gpoCalc.png)

[back to top](#top)

***

### <a name="lateOrEarlyCalc"></a>[Late or Early Retirement](https://www.ssa.gov/OACT/quickcalc/early_late.html)
[https://www.ssa.gov/OACT/quickcalc/early_late.html](https://www.ssa.gov/OACT/quickcalc/early_late.html)

**Takeaways**
* This might be for a slightly different audience - users who are slightly younger (50) and want to plan when they can go on retirement
* The results are not dynamic - it will be 90% of "primary insurance amount", but if a user is only coming here to see when they retire, they might not know how much that is
* UX
  * Small Fields
  * Results come back in a text box

**Next Steps**
* While this might be an ad hoc calculator, it needs more functionality to be useful.
* Possibly consider combining this with a benefits calculator or bridging from this calculator to a benefits calculator ("Want to estimate what 90% of your primary insurance amount? Continue to the next step and find out")


![Early or Late Retirement](images/earlyOrLateRetirement.png)

[back to top](#top)

***

### <a name="expectancyCalc"></a>[Life Exceptancy Calculator](https://www.ssa.gov/OACT/population/longevity.html)
[https://www.ssa.gov/OACT/population/longevity.html](https://www.ssa.gov/OACT/population/longevity.html)

![genderandAge](images/lifeExpectancyGenderAndAge.png)

![result](images/lifeExpectancyResult.png)

[back to top](#top)

***

### <a name="beneCalc"></a>[Online Benefits Calculator](https://www.ssa.gov/benefits/retirement/planner/AnypiaApplet.html) - Same as WEP Calculator

![Date of Birth](images/beneCalcdob.png)

![Retirement Age](images/beneCalcRetirementAge.png)

![Today or Future Dollars](images/beneCalctodayOrFuture.png)

![Annual Earnings](images/beneCalcAnnualEarnings.png)

![2021 Earnings](images/beneCalc2021Earnings.png)

![2022 Earnings](images/beneCalc2022Earnings.png)

![Results](images/beneCalcCalculate.png)

![Benefits Eligibility](images/beneCalcBenefitEligibilityResults.png)

![Benefits Estimate](images/beneCalcBenefitestimatesResults.png)

[back to top](#top)

***

### <a name="quickCalc"></a>[Quick Calculator](https://www.ssa.gov/OACT/quickcalc/)

![Quick Calculator](images/quickCalc.png)

![Quick Calculator Results](images/quickCalcResults.png)

[back to top](#top)

***

### <a name="ageCalc"></a>[Retirement Age Calculator](https://www.ssa.gov/benefits/retirement/planner/ageincrease.html)

![ageCalc](images/retirementAgeCalc.png)

![ageCalcResult](images/retirementAgeResult.png)

[back to top](#top)

***

### <a name="earningsTestCalc"></a>[Retirement Earnings Test Calculator](https://www.ssa.gov/OACT/COLA/RTeffect.html)

![Retirement Earnings Test Calculator](images/earningsTestCalc.png)

![Retirement Earnings Test Result](images/estimateBenefitReductionResult.png)

[back to top](#top)

***

### <a name="bestCalc"></a>[SSA Benefit Eligibility Screening Tool](https://ssabest.benefits.gov)

![Benefit Eligibility Screening Tool](images/BEST.png)

*Questions from Benefit Eligibility Screening Tool*
* What is your date of birth?
* Choose the option that best describes your citizenship status:
  * U.S. Citizen
  * U.S. National
  * Non-Citizen legally admitted to the U.S.
  * Other
* In which U.S. State or Territory do you live?
* Are you currently married?
* How many times have you been married? (0-10)
* Are you disabled?
* Are you partially blind?
* Choose the option that best describes where you live:
  * Private residence
  * Nursing home (cost paid by Medicaid)
  * Jail or correctional facility
  * Other facility
  * Other
* How much do you earn each month from working?
* Do you have any children that have passed away?
* Are either of your parents (including adoptive parents or stepparents) deceased?
* Are you or your spouse, parents or children currently receiving, or possibly eligible to receive, benefits from any of the following programs? (Check all that apply.)
  * Supplemental Nutrition Assistance Program (formerly Food Stamps)
  * Special Supplemental Nutrition Program for Women, Infants, and Children (WIC)
  * Temporary Assistance for Needy Families (TANF)
  * Unemployment Benefits
  * Medicaid
  * Medicare
  * Federal Pell Grant
  * A private traditional pension plan that has ended
  * None of the above

[back to top](#top)

***

### <a name="windfallCalc"></a>[Windfall Elimination Provision](https://www.ssa.gov/benefits/retirement/planner/anyPiaWepjs04.html)

![Date of Birth](images/WEPdob.png)
![Age At Retirement](images/WEPageAtRetirement.png)
![Today or Future Dollars](images/WEPtodayOrFutureDollars.png)
![Non-covered Pension Amount](images/WEPNon-Covered.png)
![Annual Earnings](images/WEPAnnualEarnings.png)
![2021 Earnings](images/WEP2021Earnings.png)
![2022 Earnings](images/WEP2022Earnings.png)
![Calculate](images/WEPCalculate.png)

![Benefit Eligibility Result](images/WEPBenefitEligibilityResult.png)
![Benefit Estimator Result](images/WEPBenefitEstimatorResult.png)

[back to top](#top)

***



## Questions for SME
1. What is the difference between retirement benefit and pre-retirement benefits? [[source](https://www.ssa.gov/benefits/retirement/learn.html#h1_)] Specifically, on the site it says "On average, retirement beneficiaries receive 40% of their pre-retirement income from Social Security."


2. How are the credits for determining eligibility accumulated? The site states "If you were born in 1929 or later, you need 40 credits (usually, this is 10 years of work)."
[Answer](https://www.ssa.gov/benefits/retirement/planner/credits.html): Earn 1 credit for every $1,470 with a max of 4 credits per year


3. On the [military page](https://www.ssa.gov/benefits/retirement/planner/veterans.html), it states "There are no special extra earnings credits for military service after 2001." Is this because active duty members after 2001 already have social security taken out from pay?


4. On the [State and Local Government Employment page](https://www.ssa.gov/benefits/retirement/planner/stateandlocal.html), what does it mean when it says "If you are covered only by your state or local pension plan"? Do some state/local government employees not pay social security taxes? It also states "Your record will show your medicare wages if you pay into that program". Is medicare taxes optional for this group of people?

5. The Windfall Elimination Provision is a little complicated. On the [site](https://www.ssa.gov/benefits/retirement/planner/wep.html) it states "The Windfall Elimination Provision reduces your Eligibility Year (ELY) benefit amount before it is reduced or increased due to early retirement, delayed retirement credits, cost-of-living adjustments (COLA), or other factors." Does this mean if you were not paying social security tax for 5 years due to a local government pension, this would push your eligibility for social security by 5 years? So an early retirement would be 67, a full retirement would be 72 and a delayed retirement would be 75?

6. Would a federal, state, or local government pension affect other non-spouse dependents?

7. On the [Government Pension Offset page](https://www.ssa.gov/benefits/retirement/planner/gpo-calc.html), it says "If you receive a pension from a government job but did not pay Social Security taxes while you had the job, we’ll reduce your Social Security spouse, widow, or widower benefits by two-thirds of the amount of your government pension." Is there such a thing as social security spouse benefit that is given to a spouse after you die? And is it separate from their own social security benefit they are receiving? Basically, this isn't saying the government pension offset will take 2/3rds of a spouse's social security that they paid into, correct? [Answer](https://www.ssa.gov/pubs/EN-05-10007.pdf): Its separate "The offset applies only to Social Security benefits as a spouse, or widow, or widower."

[back to top](#top)

## Comments
The [Working outside the US](https://www.ssa.gov/international/totalization_agreements.html) section gets a little messy and might not be necessary to add the eligibility from [international agreements](https://www.ssa.gov/international/status.html)

## Parts of Retirement
* Prepare for retirement
* retirement landing page
* Suspend payments

# <a name="todo"></a>To Do
1. ~~Map out current calculators~~
2. Diagram current prepare process
3. Write first draft on requirements

[back to top](#top)
