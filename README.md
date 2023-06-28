# Ecommerce Sales Analysis
Statistical approach towards online clothes sales analysis

## Introduction
At one point in history, a pair of good, clean clothes were considered a necessity, but times have changed.Shopping and especially buying new clothes is a leisure activity for many people. This is the domain we aretackling in this project. We have analyzed the e-commerce sale for July 2020 of summer clothes on the Wish.comwebsite. Wish is an e-commerce company that sells varieties of clothing as well as accessories and is based inthe UK. We will answer a few guiding questions that made us curious at the beginning of the project and willsummarize them using statistics.

## Guiding Questions
1. Is a product sold more just because it is priced competitively?
It is not wrong to assume that pricing a product low can lead to good sales. However, since economic conditionsof people improve, priorities that govern a person’s buying choices change. We fi nd out here that is price a factorin the number of units sold for products? We perform proportion test for the same.
2. Does the color of the clothes aff ect the sales?
Choosing a color is a subjective thing for most but certain colors might be preferred by people more than others.Since we are looking at summer data, we will be dividing the colors into “warm” and “cool” categories and fi gureout if selling clothes from a certain category of colors can bring in more sales.
3. What factors aff ect product ratings?
Ratings are an important marker for a customer to see if a product is good or not. Hence, to know from where agood rating count can be achieved is crucial for a company. We compare ratings for products based on theirshipping prices, number of shipping countries, product has been given an ad-boost or not, if it has specialbadges that signify if that product is of good quality, availability of fast shipping or products being made locally.We performed AOVA, linear regression and permutation test to answer this question.
Data Source and Preparation
The dataset used is taken from Kaggle. It is a public dataset and has been permitted for general use. Essentially,this data fi nds its origin from Wish Uk’s e-commerce platform. It is a subset of total sales data showing thesummer sales for July 2020, and contains 43 columns and 1574 rows.

## Conclusion
It was very interesting data set to work on as our Null Hypothesis was rejected in some scenarios and insome cases, we did not reject our Null Hypothesis.
To give the marketing or sales team an analysis of what factors aff ected Sales in the UK on Wish’s platform,we can confi dently say that:
Price does not aff ect sales volume (inferred from question 1).
Product color aff ects sales volume. Buyers preferred cool colors over warm colors (inferred fromquestion 2).
Shipping fee did not aff ect product ratings while products that were shipped to more countries had aweak positive correlation to product ratings. Therefore, making a product available globally doesn’tincrease product ratings (inferred from question 3).
Ad-boost aff ected product ratings in a negatively way. This means that customers do not likeproducts that are boosted through advertisement or else there are factors in play here that are havinga negative eff ect on the ratings for products there are ad-boosted (inferred from question 3).

## References
Morgan Stanley,2022, Global E-Commerce Growth Forecast 2022,
https://www.morganstanley.com/ideas/global-ecommerce-growth-forecast-2022
(https://www.morganstanley.com/ideas/global-ecommerce-growth-forecast-2022)
Crunching the Data. (n.d.). Data Science Project Proposals. Retrieved from
https://crunchingthedata.com/data-science-project-proposals/ (https://crunchingthedata.com/data-scienceproject-
proposals/)
JEFFREY MVUTU MABILAMA, 2020, Summer Clothes Sales [ Dataset], Kaggle
https://www.kaggle.com/datasets/jmmvutu/summer-products-and-sales-in-ecommerce-wish
Link to the license
https://creativecommons.org/licenses/by/4.0/ (https://creativecommons.org/licenses/by/4.0/)
Wish.com, 2023,
https://www.wish.com/ (https://www.wish.com/)
