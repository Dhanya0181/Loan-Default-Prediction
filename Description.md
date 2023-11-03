#Loan Default Prediction

I did this as a part of Data Science Challenge in Cousera.

#Introduction

The aim of the project is to predict whether the individuals will make a loan default or not given their details.
Our interest in understanding the likelihood of each individual to default on their loan payments so that resources
can be allocated appropriately to support these borrowers. 

train.csv contains 70% of the overall sample (255,347 borrowers to be exact) and importantly, will reveal whether or not the borrower 
has defaulted on their loan payments (the “ground truth”).

The test.csv dataset contains the exact same information about the remaining segment of the overall sample (109,435 borrowers to be exact), 
but does not disclose the “ground truth” for each borrower. 

We will make the output in the format : The first column as LoanID so that we know which prediction belongs to which observation. 
The second column is predicted_probability which is a numeric column representing the likelihood that the borrower will default.
