#**Amazon_Vine_Analysis**

##**Overview of the analysis**
In this project, we used some big data technologies, Hadoop, cloud services, NLP (Natural Language Processing) to analyse our datasets. These tools are mostly designed to facilitate big data analysis. During this project, we assessed the user reviews of Amazon. Sellby, a client of BigMarket, has requested for a comparison of the reviews of their products, with the competitors. Sellby is also investigating if it will be beneficial to enroll in a program where the end users are given free products to review.

##**Results**
For this project, I selected Software reviews dataset from the Amazon Review Datasets. After creating a dataframe using PySpark libraries, applying the filter function on the data frame, I selected particular rows for analysis. Finally, the votes under the paid Vine program vs. the votes exclusive to the Vine program were filtered.
The results of all reviews, 5-star reviews percentage under Vine program and non-Vine programs are shown in the following image:

![reviews_results.png](https://github.com/zkt2018/Amazon_Vine_Analysis/blob/main/reviews_results.png)

##**Summary**
Analysis of this dataset demonstrates a negative bias using the Vine program. The percentage of 5-star non-Vine program reviewers is more than %98 vs. the %1.40 for the Vine program reviewers. Hence, based on our analysis, enrolling in Vine program would not be beneficial. However, that would also be beneficial if we calculate the percentage of the total reviewers attending the Vine program vs. non-Vine reviewers. In addition, results might be different depending on the product. Therefore, it is recommended to analyze more datasets and compare them together using the filter and select functions.
