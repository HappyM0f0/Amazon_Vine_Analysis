# Amazon_Vine_Analysis

### Overview of the analysis of the Vine program:
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are required to publish a review.

The purpose of this analysis of the US Video Games data set using PySpark is to find any bias toward favorable reviews from Vine members.

### Results:
There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)

**How many Vine reviews and non-Vine reviews were there?**
- 94 Vine reviews and 40,471 Non-Vine reviews
![Total Views](https://github.com/HappyM0f0/Amazon_Vine_Analysis/blob/main/Resources/total_reviews.png)

**How many Vine reviews were five stars? How many non-Vine reviews were five stars?**
- 48 Vine reviews were also five stars and 15,663 non-Vine reviews were five stars

**What percentage of Vine reviews were five stars? What percentage of non-Vine reviews were five stars?**
- Of the Vine reviews, 51% were five stars, and of non-Vine reviews, 38% were five stars.
![Percent Views](https://github.com/HappyM0f0/Amazon_Vine_Analysis/blob/main/Resources/percent_reviews.png)

### Summary:

**The summary states whether or not there is bias, and the results support this statement (2 pt)**

Reviewing the current data, 51% of Vine reviews submitted are five stars compared to non-Vine reviews at 38%. Although the data shows a positive bias with Vine Reviewers, a larger sample pool similar to non-Vine reviewers would provide better insight on if Vine reviews are inherently positive bias. 

**An additional analysis is recommended to support the statement (2 pt)**

Further analysis on reviews greater than three stars can provide a larger sample size to further understand if Vine Reviewers tend to favor five star reviews over three and four star reviews.