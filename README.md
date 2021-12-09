# tfa-final-project
Group 16: Ellen Wang, Kathy Qian

Out of the two members of our group, we pick "10036" as our ZIP code.

In a first Jupyter notebook called Top10.ipynb, 
we analyzed what the top 10 causes of calls to 311 are in your chosen ZIP code, 
and calculated how many total incidents of each of these 10 types there have been in the year 2020. 


In a second Jupyter notebook called Parking.ipynb, 
we analyzed whether illegal parking incidents are a larger fraction of total 311 incidents in our chosen ZIP code than they are in general. 
Specifically, compute the total number of parking incidents in your ZIP, and the total number of all incidents 
-- is this fraction greater than or smaller than the total fraction of parking incidents across all ZIP codes? 
The answer is in the form of a single bool called `higher_parking_proportion`,
which is True if your ZIP contains a higher proportion of parking incidents than the global value, and False otherwise. 
For instance, if there were 200 parking incidents in your ZIP, and 1000 total incidents in your ZIP, a rate of 20%, 
but the global parking incident rate was 3000 parking incidents out of 10000 total, a ratio of 30%, 
we would assign higher_parking_proportion = False.
