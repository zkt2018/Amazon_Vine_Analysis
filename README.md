# **Amazon_Vine_Analysis**

## **Overview of the analysis**
In this project, we used some big data technologies, Hadoop, cloud services to analyse our datasets. These tools are mostly designed to facilitate big data analysis. During this project, we assessed the user reviews of Amazon. Sellby, a client of BigMarket, has requested for a comparison of the reviews of their products, with the competitors. Sellby is also investigating if it will be beneficial to enroll in a program where the end users are given free products to review.

## **Results**
For this project, I selected Software reviews dataset from the Amazon Review Datasets. After creating a dataframe using PySpark libraries, applying the filter function on the data frame, I selected particular rows for analysis. Finally, the votes under the paid Vine program vs. the votes exclusive to the Vine program were filtered.
Part of the statistics resulted from the dataset is displayed below, however, as the dataset is significantly imbalanced, it requires more analytics before a definite conclusion is made.

* All reviews:
![total_reviews.png](https://github.com/zkt2018/Amazon_Vine_Analysis/blob/main/resources/total_reviews.png)

* All 5-Star Reviews

![total_five_stars.png](https://github.com/zkt2018/Amazon_Vine_Analysis/blob/main/resources/total_five_stars.png)

* Vine 5-Star Reviews (out of all 5-Stars)

![vine_five_stars.png](https://github.com/zkt2018/Amazon_Vine_Analysis/blob/main/resources/vine_five_stars.png)

* Non-Vine 5-Star Reviews (out of all 5-Stars)

![non_vine_five_stars.png](https://github.com/zkt2018/Amazon_Vine_Analysis/blob/main/resources/non_vine_five_stars.png)

## **Summary**
Analysis of this dataset demonstrates a negative bias using the Vine program. The percentage of 5-star non-Vine program reviewers is more than %98 vs. the %1.40 for the Vine program reviewers. Hence, based on our analysis, enrolling in Vine program would not be beneficial. However, that would also be beneficial if we calculate the percentage of the total reviewers attending the Vine program vs. non-Vine reviewers. In addition, results might be different depending on the product. Therefore, it is recommended to analyze more datasets and compare them together using the filter and select functions.
