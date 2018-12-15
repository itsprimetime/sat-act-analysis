## Problem Statement


### Background
The College Board is a not-for-profit organzation best known for adminstering a fee-based standardized test for college admissions known as the SAT.

In 2011, another standardized test for college admissions, the ACT, surpassed the SAT in terms of total test takers. This prompted the SAT to release a new format in March 2016 to better align with collegiate expectations and legislative objectives.

In order to examine how the SAT can increase marketshare and revenue, I compared participation rates from SAT and ACT datasets for the years 2017 and 2018.

#### Data
In this exercise, we evaluated SAT & ACT datasets from 2017 and 2018. 

#### Conculsions / Recommendations
We identified the MidWest as a region to focus our efforts - particularly in states such as Ohio, Minnesotta, and Illinois. We observed the largest gaps in participation rates in these regions often because the ACT has statewide commitments. The College Board should pursue statewide committments such as the agreement signed with Illinois in 2017. 

Also, we observed that students in the regions tend to have a higher Total Score than other regions due to the fact that students who take the non-mandatory SAT tend to select the test and are better prepared than those students who take the test as a graduation requirement. These are helpful outcomes to use in negotiation.


### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|State Name| 
|sat_participation_rate_2017|float|SAT|The percent of high school students in the state that took the SAT in 2017| 
|sat_reading_writing_2017|int|SAT|The average score on the Evidence-Based Reading and Writing section on the SAT|
|sat_math_2017|int|SAT|The average score on the Math section on the SAT|
|sat_total_2017|int|SAT|The average total score on the SAT by State in 2017|
|act_participation_rate_2017|float|ACT|The percent of high school students in the state that took the ACT in 2017| 
|act_english_2017|float|ACT|The average score on the English section on the ACT| 
|act_math_2017|float|ACT|The average score on the Math section on the ACT| 
|act_reading_2017|float|ACT|The average score on the Reading section on the ACT| 
|act_science_2017|float|ACT|The average score on the Science section on the ACT| 
|act_composite_2017|float|ACT|The total score on the ACT for the state in 2017| 

