# Overview

In pursuit of opening a surf & ice cream shop in Hawaii, an analysis of temperatures recorded in a database for the months of June and December were completed to determine if this would be a sustainable business all year-round. SQLite was used to perform queries for temperatures collected over several years for the months of June and December. The data was extracted into a list and then converted to a dataframe where the summary statistics describing statistical details like percentile, mean, std etc were generated.

# Results


## June Results
![alt text](https://github.com/bryhnguyen/surfs_up/blob/main/Resources/June_Summary.png?raw=true)



## December Results 
![alt text](https://github.com/bryhnguyen/surfs_up/blob/main/Resources/December_Summary.png?raw=true)


# Observations:

* The minimum temperature is 9 degrees higher and the maximum temperature is 2 degrees higher in June compared to December.
* The standard deviation of December is higher than June's, making the temperature more volatile. This would make sense with a larger range than June's.
* The count of temperatures for December is 11% lower (1517/1700) and provides a smaller sample size, but is still considerable for the analysis.

# Summary

From this data, we can infer that differences in the max temperatures are marginal with 3 standard deviations for each of the months analyzed, making the Surf & Ice Cream shop a reasonable business venture in Hawaii. We could perform additional queries for months in different season to learn more about the volatility of the weather all year-round instead of Summer and Winter months where weather might be at the lowest and highest. Another query that could be performed is a query on precipitation scores for a month in each season. Identifying weather patterns that could impact outdoor activity would be vital to an outdoor recreational activity business. 
