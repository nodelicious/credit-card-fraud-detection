Credit card fraud is an ever-growing problem in today's financial market. There
has been a rapid increase in the rate of fraudulent activities in recent years
causing a substantial financial loss to many organizations, companies, and
government agencies. The numbers are expected to increase in the future,
because of which, many researchers in this field have focused on detecting
fraudulent behaviours early using advanced machine learning techniques.
However, the credit card fraud detection is not a straightforward task mainly
because of two reasons: (i) the fraudulent behaviours usually differ for each
attempt and (ii) the dataset is highly imbalanced, i.e., the frequency of majority
samples (genuine cases) outnumbers the minority samples (fraudulent cases).
When providing input data of a highly unbalanced class distribution to the
predictive model, the model tends to be biased towards the majority samples. As
a result, it tends to misrepresent a fraudulent transaction as a genuine
transaction. To tackle this problem, data-level approach, where different
resampling methods such as undersampling, oversampling, and hybrid
strategies, have been implemented along with an algorithmic approach where
ensemble models such as bagging and boosting have been applied to a highly
skewed dataset containing 284807 transactions. Out of these transactions, only
492 transactions are labelled as fraudulent. Predictive models such as logistic
regression, random forest, and XGBoost in combination with different
resampling techniques have been applied to predict if a transaction is fraudulent
or genuine. The performance of the model is evaluated based on recall,
precision, f1-score, precision-recall (PR) curve, and receiver operating
characteristics (ROC) curve. The experimental results showed that random
forest in combination with a hybrid resampling approach of Synthetic Minority
Over-sampling Technique (SMOTE)
