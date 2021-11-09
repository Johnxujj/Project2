# Phase 2 Project
##  Real estate market analyze at King County with Regression modeling

Authors: Jiajie Xu

### Business Problem

Data analysis for King County's house sale record, using 2014-2015 house sales data from online. In order to invest new real estate, what features should future owner consider most? and what should owner don't care too much? Should owner buy a larger room than he/she actually needs?

### The Data

* kc_house_data.csv
* column_names.md


## Methods

* Pandas, numpy
* mean, Correlation Function
* plot


### Results

* According to the summary, if owner want to invest a new house. Bigger living room, waterfront, and south area of King County should be considered. Those three are the most important features when market valuate the property.
* According to the summary and seatle map, King county downtown is at west side, which means more close to downtown and US west coast is more experience. Meanwhile, older houses are usually more experience.

According to the model.summary(), bedrooms, square feet of basement and year of build are the top 3 negative features. ​

Reason：​

1. House with too many bedrooms are not as hot as house with bedrooms less than 5. ​

2. Seattle is a place less likely to snow but rich of rain. Basement is damp and dark. Besides, basement like such contains more Radon gas, and Radon is a naturally-occurring radioactive gas that can cause lung cancer. ​

3. New build house are usually far from waterfront, downtown, coastline and school, those area usually been occupied with older houses.

* From the histogram and model summary, we conclude that less bedrooms, more living room sqft and more lot sqft would increase the price. If actual bedrooms need is more than 5, more bedrooms usually get a less price house. We speculate this may because those big house are less popular and hot than bedrooms number less than 5.

## Recommendations:

After analysis, my team believe this is the best time getting into valuable house.

We would suggest：

1. Bigger living room, waterfront, and south area of King County should be considered.

2. For King county, downtown and US west coast is more experience.

3. Bedrooms no more than 5 are more popular and hot to trade.


## Limitations & Next Steps

1. With more time, I would like to look into 'zip' column see if I can find more valuable information.

2. For house sale in different months, I want to check if sale price and deal made amount change accordingly. I may need to search for more sales record in different year to get a convincing trend for that.

3. There are more features might influence price like world economic environment, Nasdaq Index, pandemic, etc. I want to merge more features to get a better model for the price prediction.
