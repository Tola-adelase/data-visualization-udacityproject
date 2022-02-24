# (Prosper Loan Data Exploration)
## by (Adetola Adelase)


## Dataset
> The prosper loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

In this project I explored 10 -15 variables in the dataset which was used in analysing the dataset. I reduced the dataset to 84853 loans with 15 features to form a new Prosper Loan Dataframe. I dropped these missing values columns and converted LoanOriginationDate column to datetime datatype.


## Summary of Findings
> The majority of the loans in the dataset are current loans. Based on the length of the payment delay, past due loans are divided into numerous classes. Completed loans make up a significant portion of the total; defaulted loans make up a small percentage, but charged-off loans make up a significant portion as well.

> The monthly income distribution still shows a clear right skew with a mean and 3 times standard deviations boundary, but we can now determine that the mode is around 5000.

> The majority of borrowers are employed, with all other categories accounting for only a minor percentage of total borrowers. Full-time work has the highest priority in small groups, followed by self-employed workers, and so on.

> There were no usual distributions. The vast majority of loans are current ones. We are not interested in any current loans because our main purpose is to determine driving elements of loan outcome.

> Because most of the values in the variable Listing Category are quite rare, we changed it to categorical and reduced the number of categories to make it easier to visualise. Debt consolidation has the highest frequency of all of the changed listing options and startup having the lowest frequency in both graph.

> The most common defaulted loan rating is actually D and among the Completed, D is also the most common rating, followed by A and so on.

The monthly stated income distribution is odd: there are a lot of outliers and a wide range, but it still has the appropriate tilt (rightly skew). The employed are majority of borrowers, with all other groups accounting for a minor percentage of borrowers, and the majority of the loans in the data set are current.

There were no usual distributions. The vast majority of loans are current ones. We are not interested in any current loans because our main purpose is to determine driving elements of loan outcome.

When comparing loan status to loan amount, defaulted credits are typically smaller than completed credits. Individuals with lower ratings are more likely to be unemployed, self-employed, retired, or working part-time. and among defaulted credits, the Prosper rating (Alpha) D is the most common.


## Key Insights for Presentation
> For the presentation, I focus on exploring the features that is used in predicting loan default and what are major factors are connected with prosper credit rating and loan performance.

> I start by introducing and going through each features individually, then how they link and interact to one another, and finally how they relate to loan defaulting and performance using the aid of different charts.

