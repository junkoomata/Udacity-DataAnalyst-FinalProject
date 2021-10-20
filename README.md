# Udacity-DataAnalyst-FinalProject
Udacity-DataAnalyst-FinalProject

(covid-19-world-cases-deaths-testing)

by (Junko Omata)

Dataset

### Data used; covid10 world cases from GitHub AwesomeData (https://github.com/awesomedata/awesome-public-datasets)

### Summary of Findings

world trend 2021 is much more than 2020

Investigated first on yearly basis of daily changes during 2020, 2021 There were no seasonal trend for both years, it is clearly increasing in cases

Also looked at new_cases_per_million vs total_cases_per_million during the same yearly basis Both showed that most of the new_cases are below 2000, hoever for this year, alot more cases under 2000, as a thick band of data as well as number of outliers far beyond 4000 so the scatter blot is spreading from left down corner to upward right, thick band of new cases around and below 2000 across to right

### vaccine rate goes up, new_cases goes down

new_cases_per_million vs people_fully_vaccinated_per_hundred, there were clear sign of negative co-relationship, vaccination rate goes up, new_cases goes down, and this was most apparent beyond 80/100 points in vaccination rate

checked on vaccination rate, Gibraltar is having more than 100 for people_fully_vaccinated_per_hundred... not too sure if this meant to be booster shots or, some people getting multiple shots, as there were no data dictionary for explanation

### islanders are doing better, is COVID political issue?

Checked on above 80/100 marks of vaccination coverage and who they are

--surprisingly, lots of islands, Gibraltar, Pitcairn, Jersey, Cayman, Falklands...

It could mean islanders are doing better for having smaller government... to act on vaccination ... then COVID is political issue, who is making or not making decisions and being able to act quick enough to save peoples lives

### highest 20 location of people_fully_vaccinated_per_hundred average
### location
Gibraltar 80.185227 /n
Pitcairn 80.143333 /n
United Arab Emirates 71.197639 /n
China 65.986667 /n
Jersey 53.360870 /n
Cayman Islands 52.687262 /n
Israel 49.993897 /n
Aruba 49.608776/n
Falkland Islands 49.490000/n
San Marino 48.625976/n
Nauru 48.412000/n
Anguilla 48.134211/n
Qatar 47.958400/n
Mongolia 47.952279/n
Turks and Caicos Islands 47.650833/n
Singapore 47.325663/n
Bhutan 46.232727/n
Uruguay 44.956543/n
Bahrain 44.924502/n
Bermuda 44.699091/n

### new_cases_per_million total_deaths_per_million
### location
Gibraltar NaN NaN /n
Pitcairn NaN NaN/n
United Arab Emirates 191.796380 157.066859/n
China 0.023127 3.209920/n
Jersey NaN NaN/n
Cayman Islands NaN NaN/n
Israel 357.326779 698.838507/n
Aruba NaN NaN/n
Falkland Islands NaN NaN/n
San Marino 330.998112 2455.267076/n
Nauru NaN NaN/n
Anguilla NaN NaN/n
Qatar 115.079333 154.344978/n
Mongolia 338.624620 115.461007/n
Turks and Caicos Islands NaN NaN/n
Singapore 27.799946 6.345428/n
Bhutan 9.003370 1.920814/n
Uruguay 384.723188 963.841467/n
Bahrain 378.343786 512.426710/n
Bermuda NaN NaN/n

San Marino's total_deaths_per_million is high despite of vaccination rate, so, not all that simple as political decision making issue

For the case of Portugal and Malta, Malta is doing twice as good for total_deaths_per_million Suspected of being islands and had smaller government benefit and being cut off by ocean surroundings.... but in this data I found hospital_admission_per_million field being twice as good as Portugal, also Malta was better than Portugal in median_age, diabetic_prevalence and gdp_per_capita, hospital_beds_per_thousand

### multiple whammy

I already had a hunch diabetic_prevalence may play a big role, from the comparison on Portugal and Malta

With new_cases_per_million vs people_fully_vaccinated_per_hundred with diabetic_prevalence graph, found a shocking upsurge in the middle of negative co-relationship around 76/100 vaccination rate

Looking at it closer ... even found worse more vivid upsurge in 30-40/100

Quad whammy for those upsurge nasty-spikes group, Cardio=high, diabetes=moderate, age=older, and smoking=moderate - high

nasty-spikes people curiously coming from neighborhood region of Romania, Serbia, Montenegro

nasty-spikes people are having lower rate of vaccine coverage up to 40

Upsurge could be diverse affect of vaccine or new variants emerging, or even possibly be manual workers came home from EU and UK... not being eligible to vaccine on road?

### Key Insights for Presentation

tracking down those nasty-spike groups

narrowing down on nasty-spike people's data ... its quite sad to see them all around in central Europe... wonder what really happened

I wish I can show the weekly new case high locations on heatmap, simulating central Europe map

heatmap generated... feeling rather upset and sad about this Romania is missing big chank of data for summer May to August... it may have been terrible as adjascent data in April is very high both in new_cases as well as new_deaths

Serbia and Montenegro upward spike is currently happening... it may be new variant emerging

Looking at worst list, lots of central Europe locations.... Hungary, Poland.... Would be interesting to see if diet high in red meat... may be affecting In fact, anything to damage blood vessel, high fat, sugar, salt .... anything will be having trigger for the new infections... and at this moment I am feeling like COVID is hacking human system weakness in different regions attacking on weakened immune persons

Before long it will discover not just obesity factor, but may be genetical weakness yet to discover, faster than us attacking relentlessly

Checked on supplementary data with WHO's dentist per 10000, this did not show any clear indication of relationship, so given up on dentists datasets

Obesity data set may be interesting, though high diabetes and high cardio are in a way another way to express obesity ....
