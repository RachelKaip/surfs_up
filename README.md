# Surf's Up!
## Overview
This week we helped our friend W. Avy conduct a climate analysis of Oahu- the island we want to open a combination suf and ice cream shop on one day!  To conduct this analysis, we wrote queries to a sqlite database that held years of climate information reported on by the local weather stations, then used Flask and Pandas data frames to help display our findings.  

After conducting a gernal analysis of Oahu's climate over the years, W. Avy wanted us to focus our efforts on just two months of the year- June and December.  For this, we wrote queries to filter the database's temperature column to only show June and Decembers' temperature, then provide a summary of statistics for each.  

## Results 
Singling out just June and December's data helped us see clearly into many temperature trends.  Three of our major findings are below:

1. The standard deviation of June's temperature is only ~3 degrees, meaning we do not need to worry about volatile temperature changes that would ward off surf and ice cream cutomers.  

![June_Df](https://user-images.githubusercontent.com/94569240/154377123-5f82244d-4101-4dad-8160-6932282696e9.PNG)

2. In the imgaes above and below, we see that the mean temperature in June is not significantly higher than that of December- about 75 and 71 degrees, respectively.  This helps us understand that this surf and ice cream shop could be profitable year-round.  

![Dec_Df](https://user-images.githubusercontent.com/94569240/154377133-1ae834ad-6525-4c99-9328-e6adc20ad17a.PNG)

3. However, the image about tells us that at some points, December can get as cold as just 56 degrees (f).  This warns us that while our shop can function year-round, there may be less-profitable days than other months.    


## Summary
Looking at the data frames we've created to analyze Oahu's temperatures in June and December has helped us understand that surfing (and therefore, ice-cream-eating) is ayear-round sport for the residents and visitors of Oahu!  However, it also warns us that, while we could operate our shop 365 days a year, we might want to adjust out inventory buying for the "colder" months, as Oahu does reach low temperatures that might ward off surfers.  

With these findings in mind, I would reccomend W. Avy and I look depper into the true cliamte of Oahu with the following two queries: 

1. Queries to find the percipitation for every day in both June and December.  This will help us narrow down our true number of popular surfing days that we can expect each month.  Example below: 

![suggestion1](https://user-images.githubusercontent.com/94569240/154377151-466b9ad9-45ad-4e2f-a695-70f4199055f6.PNG)

2. A query to see ho many days of both months that the temperature is below or equal to/above it's mean in June and December.  Same as above, the information this query would provide will help us understand how many "surfable" days are in each month.  Example below:   

![suggestion2](https://user-images.githubusercontent.com/94569240/154377166-1f62af20-1ee5-426e-9890-9958e6c1f170.PNG)
