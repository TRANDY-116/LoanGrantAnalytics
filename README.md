# (Factors Used to Determine Loan Grants)
## by (TANWIE RANDY FUNWIE )


## Dataset

The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary of Findings

In my exploration I found the majority of the loans were current loans followed by the completed then the chargedoff loans, this shows that loan have have been successfull to a certain degres. Also the majority of Borrowers were employed with few not employed or retired which shows a great factor in determining if a loan would be granted. 
I went on to assess the distribution of the Borrower rate which shows that the majority of loans granted were between 10-20% especially for the completed ones. For the chargedoff and defaulted loans there were some peaks from 28% to 33%.Which shows that loans at those rate might have a tendency of been chargedoff or defaulted. 
Looking at the relationship between the Employement Status and the borrower Rate we can see that the distribution of the rate were mostly spread around the 10-24% range which the outstanding distribution being the umemployed which shows that the majority of the rate were set at 27-31%.
One more thing I noticed was being in a group didn'r really have any relationship with the Borrower's Income Range but Looking at the graph(Income Range vs Employment Status vs IsBorrowerHomeOwner) we could see that borrowers who were home owners and also in the 100,000 dollars  had more loans granted to them except in the part time catergory where borrowers in the ($ 75,000 - $ 99,999) had more loans granted to them 


## Key Insights for Presentation
For my presentation I decided to First Look at the individaul distributions of the Loan status,Employment status and also the Borrower Rate on how there were represented in the dataset.Looking at the borrower rate I also look at the rate distribution under 3 distinct Loan status The completed,Chargedoff and Defaulted loan states.The plots didn't need any tranformation so I proceeded.

Finally I presented the Income Range vs Employment Status vs IsBorrowerHomeOwner plot which was aimed at looking how these three factors related to each other. The first was too large and difficult to read so I broke down the data to only plot the relationship of the employed.