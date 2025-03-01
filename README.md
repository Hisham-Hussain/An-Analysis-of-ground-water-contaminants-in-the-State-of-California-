# An Analysis of ground water contaminants in the State of California 
## Overview of the project

The aim of the project was to analyse and visualise the number of contaminant leaks across the state  of California with the aim of determining which county succumbed to the most leaks and to understand what contaminants constituted those leaks. 

## Dataset
The dataset used was obtained from the California state government and it is a record of an instance of a leak from companies within the state. The data contains information of the company that has reported a leak, the county and city in which they are based as well as their coordinates. Descriptions of the date of when where and how the leak were doumented as well as the actions performed to stop the leak, including the date the leak case was considered to be closed.

Furthermore, the constituents of the leak were specified as well as the the amount in gallons and what media (soil,water,etc) was to be potentially affected by the leak.

The source and cause of the leaks were also included but nearly half the entires did not have those facts disclosed.

## Analysis 
In summary, the county that had the longest days on average to report contaminat leaks were San Francisco, averaging nearly 6000 days. The county that took the longest to report a repair of the leak was Tuolomne, which averaged approximately 4500 days. These numbers may not be eniterly accuarate as several dates of the leaki beginning were entered as 2/1/1965, which would vaslty obscure the actual figures.

The top 5 contaminants were found to be gasoline, diesel, waste oil, heating oil and other solvents, with San Diego, San Francisco and Los Angeles, being counties with the majority of where those contaminats had leaked.

A correlation between the extent of a community's disadvantaged status adn the days to report and repair the leak couldnt not be deterermined due to several reasons.The median household income is required to classify a communuty as severlery disadvatnaged, and those numbers were not provided. Furthermore, there were 61,653 community classifications missing, which even if the MHI figures were avaialable, a strong correlation would not have been able to have been made. 
## Dependencies 
Pandas, matplotlib.pyplot, seaborn, follium

