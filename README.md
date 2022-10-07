# Prosper Loan Dataset Exploration
## by Folami Justin Balogun


## Dataset

> The dataset provides several details about people that listed for loans and includes details of such as loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset contains 113937 rows and 81 columns. I downloaded the data set from [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv).  
> I worked with only observations where the loan status were either completed ot charged off. I tried to gain insights on variables that may determine if loans collected will be completed or written off by the loaner(s).
> I cleaned the column titles for ease of exploration and dropped columns I didnt intend to work with and rows that did not meet certain criteria.

## Summary of Findings

> Shorter loan terms had a higher probability of being completed than longer one.
> Charged off loans were correlated with a higher median borrower annual percentage rate while completed loans had lower median borrower annual percentage rate.
> The reverse is the case for the relationship between prosper score and the loan status. A higher median score is correlatated with the loan being completed.
> I also considered the correlation of the income percentage used in servicing loans against the loan status and observed that completed loans had lower median income percentage used in servicing loans.
> Suprisingly, the loan original amount has no correlation with the loan status. Although in a multivarate relationship, It shows that charged off loans had a lower maximum amount per loan term. The reason for this however was not established.  

> Looking at the other relationships, the strongest correlation was seen between loan original amount and the monthly loan payment. The annual borrower annual percentage rate also had a decent negative correlation with the prosper score. Little to no correlation existed between monthly loan payment and the stated monthly income. 

## Key Insights for Presentation

> For the presentation, my focus was on Loan status and how it correlates with term, income percentage used to service loans, borrower annual percentage rate and prosper score can be used to predict whether a loan will be completed or charged off.
I started of by showing the distribution of loan status then I went on to show how the proportion of charged off loans increased as the loan term increased.
Next, I showed how the median income percentage used in servicing loans were smaller for completed loans than charged off loans. 
Finally, I showed the association of completed loans with lower median borrower apr and higher prosper when compared to charged off loans first in bivarate plots then all three in a multivarate plot.