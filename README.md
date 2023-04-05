# ACTL4001 Assignment - 2023 SOA Research Challenge

![image](https://user-images.githubusercontent.com/113440610/229755925-c567265f-9d0b-4fc0-908f-5311ab7433b9.png)



----------------------------------------------
## **Executive Summary**

The actuarial team at MAIVE Consulting have been tasked with designing a social insurance program for relocation. With the threat of climate change becoming apparent around the globe, Storslysia, who are no exception to the reality of climate-related catastrophes, would like our firm to help manage its exposure to displacement risk due to catastrophice weather events. 

The team has outlined three core principles that its program should adhere to. Specifically, that the benefit payable:
* Should be strictly greater for proactive relocation than for reactive relocation, to ensure incentivisation of the former. 
* Will scale based on the wealth of each household, in the social interests of Storslysia's society.
* Will vary based on the risk inherent to each household at a region level.


## **Program Description** 
MAIVE Consulting recommends that a citizen of Storslysia will be eligible to file a claim under the scheme by default. The citizen can then elect either a proactive or reactive cover.

Each cover will provide a catastrophic relief payment, as well as the following extras: transport fees; coverage for tools of trade, not including home office equipment; provision of temporary accommodation; two Ꝕ50 vouchers per adult – redeemable at select businesses, including but not limited to restaurants, furniture storage, furniture removal; and a free subscription to a mental health program (valued Ꝕ1000 per person). 

A key aim behind this program is to offer adequate support to residents relocating to a new area - whether that be financial support, or help managing after-effects of a natural disaster, for example, psychological impacts. 

The catastrophic relief payment, unlike the above extras, vary between the proactive and reactive covers.

In accordance with the control cycle, this program will be monitored by MAIVE Consulting monthly over the short-term period of the first year. This frequency will ensure that, as the program is introduced into practice, any initial inefficiencies can immediately be adjusted to improve program performance. The regularity of monitoring will then shift to a quarterly review over the next 2 years, before transitioning to biannually over the following 5 years, and finally annually thereafter for a period of 20 years. 



## **Pricing** 😮
We forecasted Storslysia's GDP and population and built our proposed program to identify costs associated utilising our [R Script](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/group-github-pages-group-1/blob/main/R%20Script).

This script also includes sensitivity analysis performed, and summary statistics to ensure the proposed program costs do not exceed 10% of Storslysia's GDP. 



## **Results** 😎
The total costs of our program from 2020 - 2100 in the worst case scenario is shown below. From our analysis, our proposed program costs will not exceed 10% of GDP.

<img width="432" alt="Screen Shot 2023-04-05 at 10 58 26 am" src="https://user-images.githubusercontent.com/113522147/229954592-73bcc59f-8e11-44d7-b64b-2f4859234875.png">


Comparing the economic costs with and without our program, we notice that with our program there is reduction in economic costs in the future as well as a decrese in variance. 

With Program                   | Without Program
:-----------------------------:|:-----------------------------:
![image](https://user-images.githubusercontent.com/113440610/229763855-fbf4e5ae-9f82-4626-9acd-d33850ac57f6.png)|![image](https://user-images.githubusercontent.com/113440610/229764395-98ef8259-a2e3-456e-8b3b-5b7e7af95167.png)

## **Assumptions**

### ***Categorisation of 'Catastrophic' Weather Events***
No existing definition of 'catastrophic' was provided. Accordingly, it was assumed using real world data that, on average, a natural disaster that causes over 5 deaths and/or 16 fatalities is 'catastrophic'.

### ***Maximum Payout for Reactive Relocation***
Property value was assumed to be a proxy for a citizen's net worth. The relevant payout was thus a floating percentage of this value. Those most socio-economically disadvantaged were assumed to be most in need of capital and thus received a lump sum almost equivalent to their property value. This sum decreased as one rose up in the property bracket. For the same reason, the percentage of contents recoverable decreased as wealth increased. Of course, where a citizen did suffer more, their payout would be the total damage caused.

### ***Currency; Number of People per Household***
The exchange rate was assumed to be 1.321. The number of individuals per household has been assumed to be 2.5 citizens.

### ***Timing of events***
Due to the need for otherwise heavy (and imprecise) interpolation, it is assumed that the claims only occur at the end of every 10 years and as such, the costs of claims will only be discounted at the end of every 10 years.

### ***Property Value Distribution; Displacement Propensities of Perils***
The distribution of property values has been assumed to stay the same. The displacement propensities of each peril have been assumed to be constant for the next hundred years. This is because it is futile to predict any change in the propensities as the rate of these extreme weather events are dependent on climate change – which, by definition, is inherently unexpected and unpredictable.

### ***Percentage of Region Affected by a Catastrophic Event(s)***
It has been assumed that the more fatal a particular type of natural disaster, the greater the proportion of a region that may likely be affected. No assumptions were made as to differentiate how each region may be affected because no information was given relating to each region’s geographical features.

### ***GDP Growth***
The investment returns on the remainder of the capital have been assumed to be included in the forecasted GDP.

### ***Baseline Assumptions***
The baseline inputs used for the model involved a 5% interest rate to discount the future claims cost to 2020 and a 3% inflation rate to inflate the cost. These assumptions were performed using data and projections from the SSP5 Scenario as this is the most extreme case that would overestimate costs.


## **Risk and Risk Mitigation Strategies**
<img width="442" alt="Screen Shot 2023-04-05 at 11 36 31 am" src="https://user-images.githubusercontent.com/113522147/229958810-2451ccc0-902d-49dd-9cf0-324f1bae9348.png">

The following strategies have been identified to mitigate these risks.

### ***Financial***
* Perform a valuation each year to ensure that costs associated with the adjusted benefits and the risk of a proactive or reactive relocation do not exceed 10% of Storslysia’s GDP and that there is adequate reserves to cover these payouts. At each valuation, adjust assumptions in the calculation of our costs to any economic or policy changes.

### ***Operational***
* Monitor the adequacy of benefits such as changing circumstances e.g. worsening climate change or unexpected population increases, and adjust benefits accordingly.
* Manage land available (Risk 4) for relocation by partnering with city planners.
* Forecast future extreme weather occurrences at different risk-levelled scenarios. Use
this forecast to inform how much funding we require to avoid ruin.
* Manage tax risk by keeping up to date with tax laws and adjusting benefits.

### ***Strategic***
* Manage unexpected resident preference by keeping up to date with local culture and adjust incentives for proactive relocation accordingly.
* Manage moral hazard (Risk 10) by ensuring out eligibility criteria is up to date, and screening claimants carefully to ensure they receive a justified amount.

![giphy](https://user-images.githubusercontent.com/113440610/229765593-73ada8b7-5573-423a-9239-31cf87defbf3.gif)

