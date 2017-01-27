# Examining NYC Gentrification From 2000 to 2010
## Process:

1) Find the number of businesses in 2010 and 2000.
2) Gather a zipcode file and merge with business data.
3) Find the density of businesses by zipcode.

### Takeaway:
Proportional change in business density throughout NYC indicates some density increases in Harlem, Downtown Brooklyn, Bed-Stuy, and Williamsburg. Midtown & The Upper East side, appear to be the only areas that clearly didn't share the trend of increasing density of business. This is likely due to the fact that they were near capacity in 2000. 

4) Collect census data.
5) Collect income data.
6) Merge census and income data.
7) Merge dataframes with census tract shapefile.

### Takeaway:
Through most of NYC there wasn't a structural trend in the percent change of population or age between 2000 & 2010. Clearly, Crown Heights, Bed-Stuy, and Harlem became whiter between 2000 & 2010. Similarly, most of Brooklyn and Harlem appear to have had an increase in income greater than the  rest of NYC between 2000 & 2010.

8) Cluster the census tracts.
9) Identify census tracts that changed cluster.

### Takeaway:
Although there are sporadic changes throughout NYC, there appear to be groups of cluster changes in lower Manhattan, Williamsburg, and Harlem.

10) Aggregate census tracts to the zipcode.
11a) Display each feature and the change of each.

### Takeaway:
Age and population change don't show an apparent change. However, white population, income, and business density appear to have all increased in Harlem and most of Northwestern Brooklyn.

11b) Cluster zipcodes on our 5 features.
11c) Identify zipcodes that changed cluster.

### Takeaway:
Here, we can see changes in clustering around Chelsea, Harlem, and Northwestern Brooklyn.

12) Define a function to ID cluster changes.

# Summary of Findings
Through this analysis we can see that there have been demographic changes in Chelsea, Harlem, Lower East Side, and Brooklyn (along the East River). Interestingly, the change in clustering in Staten Island reflects land use changes. Nonetheless, although this analysis was able to broadly identify areas of gentrification, it is limited to the variables examined here. Specifically, population density would be a better metric than mean census tract population (as used at the Zipcode level). Moreover, although this analysis is an interesting exploration into the spatial relationship of commonly recognizeable features of gentrification, there are likely issues of autocorrelation. Ultimately, a next step may be to conduct feature selection on the underlying census data to see what features best explain differences between different NYC neighborhoods.