
**Loan Default Prediction Project**

**Objective:**
The objective of this project was to predict the likelihood that an individual would default on their loans using various numerical and categorical factors. 
This prediction is crucial for financial institutions to manage risk and make informed lending decisions.

**Data Overview:**
The dataset consisted of several hundred records, each representing an individual’s profile. 
Features included demographic information, financial history, and loan details. The dataset was somewhat imbalanced, with feIr cases of defaults compared to non-defaults.

**Exploratory Data Analysis (EDA):**
I performed extensive EDA using heatmaps, histograms, and bar charts to understand the relationships betIen features and the target variable. 
For instance, I found that certain features like credit scores had moderate correlations with loan default rates, but most features had little/no correlation with loan default rates. 
These insights guided our feature engineering process.

**Feature Engineering:**
I created new features total income (combinination of spouse and individual income. 
Categorical features Ire encoded using techniques like one-hot encoding and target encoding. These engineered features helped improve the model’s predictive poIr.

**Modeling:**
I initially chose a logistic regression model due to its simplicity and interpretability. I also experimented with other models like decision trees and random forests, but logistic regression provided a good balance betIen performance and interpretability.

**Evaluation:**
The model’s performance was evaluated using confusion matrices, precision and recall. 
The logistic regression model achieved an overall accuracy of 79%.

**Results and Impact:**
The final model may provide value to organizations that lend money such as banks, allowing them to better manage their loan portfolios and reduce default rates. 
By focusing on high-risk individuals, the institution could take preemptive measures, such as offering financial counseling or adjusting loan terms.

**Future Work:**
Future work could include exploring more advanced models like gradient boosting machines or neural networks, and adding more features.
