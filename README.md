**Titanic Machine Learning Competition**
**Description**
The Titanic disaster remains one of the most infamous shipwrecks in history. On April 15, 1912, the RMS Titanic sank after hitting an iceberg during its maiden voyage. Tragically, there were not enough lifeboats for all passengers and crew, resulting in the loss of 1,502 lives out of 2,224 onboard.

This competition invites participants to build a predictive model to determine the likelihood of survival based on passenger data, including features such as name, age, gender, and socio-economic class. The central question is: "What kinds of people were more likely to survive?"

**Approach
Model Used**
For this competition, a Random Forest classifier was employed to predict passenger survival. Random Forest is an ensemble learning method that combines multiple decision trees to improve predictive accuracy and control overfitting.

**Model Evaluation**
The performance of the Random Forest model was evaluated using several metrics:

Accuracy: The proportion of correctly predicted survival outcomes.
Precision: The proportion of true positive predictions among all positive predictions.
Recall: The proportion of actual positives correctly identified by the model.
F1 Score: The harmonic mean of precision and recall, providing a balanced measure of performance.
Cross-validation was utilized to ensure the model's reliability and generalizability, helping to prevent overfitting and validate its effectiveness on unseen data.
