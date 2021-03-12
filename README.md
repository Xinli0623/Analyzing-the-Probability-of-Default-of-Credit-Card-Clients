# Analyzing the Probability of Default of Credit Card Clients



For this project, I used Python (sklearn, dmba, tensorflow) to train six classification techniques in data mining including Logistic Regression, Decision Tree, Naive Bayes, Gradient Boosted Tree, Random Forest, and Neural Networks to predict whether a credit card client will default on the bill of next month based on demographic information and repayment history of last 6 months. 

Firstly I built 6 models and compared their performance. I selected accuracy, f1-score and AUC as model metrics. Then I selected 4 top performed model to optimize parameters using Grid search. I also used stacking in the project as an optimization and got better performance than single models.

* **Business Problem**
* **Dataset Overview**
* **Data Preprocessing**: dummy coding, split data into train test sets.
* **Build Basic Models**: build models, feature importance, model metrics, ROC curve analysis
* **Parameter Optimization**: Gird Search, TensorBoard
* **Stacking**: logistic regression, random forest, decision tree
* **Conclusions**

Through EDA and feature importance analysis, I got some insights about risk management. Like, these clients who have defaulted in the past one to two months are more likely to default on bills next month. Clients with lower education levels are more likely to default on bills.

