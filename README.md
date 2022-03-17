# Basics-of-Deep-Learning

# 1. Defining the Question
# a) Specifying the Data Analysis Question
Identify the factors that could predict whether an employee will get promoted or not.

# b) Defining the Metric for Success
This project will be considered a success when:
1. we are able to confidently determine which employees are likely to get promoted, and
2. we get at least one model with an accuracy score of around 80%.

# c) Understanding the Context
You work for Alphabet Inc. which is a large Multinational Corporation. The company has 9 broad verticals across the organisation. One of the problems the company is facing is around identifying the right people for promotion (only for the manager position and below) and prepare them in time

Currently the HR process, they are following is:

They first identify a set of employees based on recommendations/ past performance.
Selected employees go through the separate training and evaluation program for each vertical.
These programs are based on the required skill of each vertical. At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., the employee gets a promotion.
For the above-mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, the company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

# d) Recording the Experimental Design
1. Load dataset and libraries.
2. Clean dataset.
3. Carry out univariate and bivariate analysis.
4. Determine which employees are likely to be promoted based on the results of the analysis.
5. Carry out data modeling.
6. Summarize findings.
7. Provide recommendations.
8. Challenge the solution.

# e) Data Relevance
The data provided is sufficient and appropriate for answering the research question.


# 5. Summary of Findings
The neural network accuracy is currently at 93.7%

# 6. Recommendations
We can Improve the Neural network by:
1. Optimising the number of layers and nodes per layer
2. Repeatedly exposing the model to examples of input and output and adjusting the weights to minimize the error of the model's output compared to the expected output

# 7. Challenging our solution
a) Did we have the right question?
Yes, the question could be solved using classifier models & building an artifical neural network

b) Did we have the right data?
Yes, the data was sufficient to determine promotion.

c) What can be done to improve the solution?
We can incorporate a holdout validation set to ensure the models and neural network did not overfit. we can also incorporate larger amounts of data
