# Analysis of Flight Delays
## by Robert Hofstetter

## Data Source

> The data for this analysis was obtained from the [Bureau of Transportation Staticis](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236). All domestic United States regions for years 2018 and 2019 were download by month and concatenated together outside of this notebook into two separate files for each year. It is a rather large set of data so I've separated the cleaning in order to speed processing of later cells.

## Findings
> I found that of all the features examined the number of flights, or trips, is a good predictor of the length of delay. This information could be used to recommend reasonable connection times to help avoid missed connections among other things.

## Resources
> I leveraged various lessons from my Udacity learning along with internet searches for topics not covered including: seaborn.pydata.org to determine how to set facet grid titles.