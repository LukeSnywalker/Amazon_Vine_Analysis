# Amazon Vine Analysis
 
## Overview

The purpose of this project is to analyze a database of video game reviews on Amazon to determine whether there is a positivity bias among reviews in the Vine program (i.e., if there are more five-star Vine reviews than five-star non-Vine reviews).

## Results

In Vine_Review_Analysis.ipynb, a DataFrame was created that displayed the star ratings, numbers of helpful votes and total votes, and Vine or non-Vine status for each review in the video game review database. Throughout steps 1 to 4, this DataFrame was filtered to retrieve only the most helpful votes, and two new DataFrames were created, each containing either the Vine or the non-Vine reviews.

The following methods were applied to retrieve the statistics below:
![The code used to retrieve the summary statistics](/step_five_code.png)

* There were 94 Vine (paid) reviews and 40,471 non-Vine (non-paid) reviews.
* There were 48 five-star Vine reviews and 15,663 five-star non-Vine reviews.
* About 51.06 percent of the Vine reviews were 5 stars, while about 38.70 percent of the non-Vine reviews were five stars.

## Summary

* Although only slightly more than half of the Vine video game reviews were five stars, there appears to be a slight positivity bias among the Vine reviews compared to the non-Vine reviews. However, the sample size of Vine reviews was much smaller than the sample size of non-Vine reviews, and we are only looking at the frequency of five-star reviews, which does not give us an accurate comparison of overall positivity. Another analysis we could perform to strengthen our conclusion could be to collect random samples of at least 50 Vine and non-Vine reviews, and then performing a chi-squared test to determine if there is a significant different in the frequencies of each amount of stars (1-star to 5-star) between Vine and non-Vine reviews. 