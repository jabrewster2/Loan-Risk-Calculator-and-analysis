# Loan-Risk-Calculator-and-analysis
# Executive Summary
Borrower's default rates are higher than the bank wants them to be and we need to find a way to select better candidates for loans. Using Python to create and train a random forest machine learning model to predict good candidates, we can take borrower's data to provide valuable insights about if they are a right choice to lend to and accurately predict if they are probable to default 91% of the time. 

# Business Problem
Consumer and community banks generate a majority of their income through small loans to members of their community by charging the borrower interest on the loan. The managers of the bank and the stakeholders realized that default rates on their loans (the number of people failing to meet payments) has gone up and wondered how to filter their applicants better so they can continue to make smart investments. Using simple information about the borrower based on their loan application can we develop a filtering method to provide loans to people who will likely repay their loans?

# Methodology
1. Clean borrower data using Pandas so it can be analyzed using Python and Sklearn.
2. Analyze the data and feed it into a random forest machine learning model to predict who will default.
3. Report findings using Matplotlib and Sklearn to visualize the generated tree.

# Skills
Python: Pandas, Matplotlib, Numpy, Writing functions, statistics

# Results and Business Recommendation
This analysis shows that the major factors in deciding if a borrower will default are the loan's percentage of income, the loan's grade, and the borrower's income. Factors like the borrower's age and what they are going to use the loan for are not very relevant in prediction. My recommendation to the bank is to implement this machine learning model to help bankers determine if the borrower is right for the loan. The bank can use the model as a starting point and a filter to save time and dedicate more time into the cases that sit on the fence while the model continues to learn from new borrowers from the bank. 

Below is the tree the model came up with to categorize borrowers and the most important information about their loan that makes them acceptable or not.
<img width="1899" height="1079" alt="image" src="https://github.com/user-attachments/assets/c5ad9e03-3f1c-4ea2-aeb7-be43976919eb" />
<img width="700" height="415" alt="image" src="https://github.com/user-attachments/assets/7b860158-bf95-4cd7-93a2-e58b84890986" />

# Next Steps
1. Run testing on banks with and without this model and determine to implement it to all locations.
2. Gather more borrower data so model can make more informed decisions.
3. Measure borrower default rates after the implementation of the model.
