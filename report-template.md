# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * The logistic regression model, when applied to the original imbalanced dataset, exhibits commendable predictive accuracy, as evidenced by a balanced accuracy score of 94.4%. Detailed analysis via the classification report reveals a nuanced performance: for the 'healthy loan' category (label 0), the model achieves perfect precision and recall, both at 100%. Conversely, in identifying 'high-risk loans' (label 1), the model demonstrates robust precision at 87% and recall at 89%, indicating a high level of accuracy in distinguishing between the two loan conditions. This nuanced performance highlights the model's strong capability in handling both straightforward and complex prediction tasks within an imbalanced data context.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Leveraging oversampled data, the logistic regression model achieves superior predictive accuracy, as reflected by an impressive balanced accuracy score of 99.6%. The classification report provides a deeper insight into its performance: for identifying 'healthy loans' (label 0), the model reaches an optimal precision and recall, both at a flawless 100%. In the case of 'high-risk loans' (label 1), the model maintains a precision of 87% but elevates its recall to a perfect 100%. This enhanced performance illustrates the model's exceptional ability to accurately classify both loan categories, benefiting significantly from the balanced distribution achieved through oversampling.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
* The second machine learning model, which leverages oversampled data, distinctly outshines its counterpart in terms of performance, as evidenced by its superior balanced accuracy score. The strategic use of resampled data, ensuring an equitable distribution of labels, significantly enhances the model's precision and recall metrics, as detailed in the classification report. This methodological approach not only rectifies the imbalance inherent in the original dataset but also optimizes the model's ability to accurately predict and classify with greater confidence and reliability.