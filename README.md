# Credit-Card-Approval-Classification

Num Bullet Points 
1. Both train data and test data are imbalanced (defaulted: non-defaulted = 1:9)
2. Three features (‘pct_card_over_50_uti’ etc.) have missing values
3. Suspicious data detected regarding credit age, numbers of account due, etc.
4. 5 groups of numerical features are highly correlated
5. 7 discrete numerical features are right-skewed, while others are normally distributed
6. Synthetic Minority Over-Sampling (SMOTE) is applied to balance the data
7. Logistic Regression, Decision Tree, Random Forest, and Gradient Boost are compared
8. Hyper-parameter tuning and model evaluation for Logistic Regression and Random Forest
9. Feature interpretation and importance analysis
10. Model future application by scoring and ranking
