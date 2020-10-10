# Prosper Loan Exploration

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others 


## Summary of Findings

In my exploration, I found a strong relationship between the borrower ’s interest rate and the average credit score. The relationship is that the borrower ’s interest rate is approximately negatively linear with the average credit score, but the higher the average credit score, the slower the borrower ’s interest rate decline.

I also found an interesting relationship between borrower ’s interest rate and debt-to-income ratio. By directly plotting a scatterplot between the borrower ’s interest rate and debt-to-income ratio, I could n’t see a clear relationship, which surprised me. Therefore, I added a new variable "CreditGrade", which shows a positive linear relationship between the borrower's interest rate and debt-to-income ratio in each credit rating category.

Not surprisingly, I noticed that higher credit ratings and higher prosperity scores also result in lower borrower interest rates.
In addition, I see that homeowners prefer to have higher average credit scores and lower borrower interest rates. Employed borrowers, especially full-time borrowers, may also have higher credit scores and lower Borrower's interest rate.

In addition, I found that the borrower ’s interest rate became more and more sensitive to changes in credit scores over time. This is reasonable for an economy that has grown steadily and grown steadily in the United States since the 2007 financial crisis.
Finally, I noticed that when the term is longer, the borrower ’s interest rate and average credit score will be more concentrated. I think this makes sense, because long-term interest rates are usually more stable than short-term interest rates.

In addition to the main variables of interest, I found that borrowers who are employed or employed full time are usually homeowners.


## Key Insights for Presentation

In the presentation, I focused on the relationship between the borrower’s interest rate and other variables. I first introduce
I think the relationship between the borrower ’s interest rate and the distribution of the average credit score is the closest to the borrower ’s interest rate.

Then, I introduce the relationship between the borrower's interest rate and the average credit score, credit rating and prosper score.

Then, I explained the relatively strong relationship between the borrower’s interest rate and debt-to-income ratio by dividing records by credit rating.

Finally, I used a heat map to show the relationship between borrower interest rates among other categorical variables (including IsBorrowerHomeowner, EmploymentStatus, year, and Term), and explained the distribution of records and the attributes of each category.