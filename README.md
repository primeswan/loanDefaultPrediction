# Loan Default Prediction

## The problem
This is a [Coursera](https://hub.labs.coursera.org:443/connect/sharedofzckbhc?forceRefresh=false&path=%2Fnotebooks%2FLoanDefaultPrediction.ipynb&isLabVersioning=file-prep) project for predicting loan defaults.
Training data of 250k entries and a test data of 100k entries was given. True predictions for the evaluation data are only revealed once the project is submitted as part of the competition.

## The solution
I achieved project objectives (maximizing ROC AUC score on test data) by employing logistic regression on the small dataset. While advanced algorithms did not perform well due to data size, logistic regression provided high predictability on test data. By assigning probabilities to loans,  tailor targeting for better decision-making is possible.

## The approach
To complete the project, I conducted thorough data analysis, exploring correlations, utilizing graphs, and identifying feature interactions. I then set performance benchmarks using advanced algorithms but opted for logistic regression, given the dataset's size. Leveraging domain knowledge, I fine-tuned the model, resulting in interpretability and high accuracy.

## The results
In the competition, with ~76% ROC_AUC score on test data, the project achieved 100th percentile in evaluation among peers. The attached [file](/LoanDefaultPrediction.pdf) in this repository has the final model code.
