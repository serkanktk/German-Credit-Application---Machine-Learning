# German-Credit-Application---Machine-Learning


In our project, we conducted an in-depth analysis of machine learning algorithms to predict credit risk using the German Credit Data. We preprocessed the data to address missing values and convert categorical features into a suitable format for model ingestion. Subsequent to preprocessing, we split the data into training and testing sets to assess the performance of our models.

Our experimentation involved fine-tuning models like Logistic Regression, MLP (Multi-Layer Perceptron), KNN (K-Nearest Neighbors), Decision Trees, and XGBoost, with a specific focus on optimizing their hyperparameters through grid search and cross-validation methods.

Here’s a concise summary of our findings and methodologies:

- We applied Logistic Regression as a base model and improved its accuracy from 0.708 to 0.728 by incorporating Recursive Feature Elimination (RFE), which helped in identifying the top 10 most predictive features.

- Both the MLP and KNN models achieved a competitive accuracy of 0.716, indicating their efficiency in the classification task despite their differing approaches (neural network vs. proximity-based classification).

- The Decision Tree algorithm presented a lower accuracy of 0.672, implying a limitation in capturing the intricate relationships within this specific dataset.

- XGBoost showed a promising performance with an accuracy of 0.72, reflecting the power of gradient boosting techniques in classification problems.

The most effective model, Logistic Regression with RFE, displayed a propensity for false positives as revealed by the confusion matrix. This underlined the model's conservative stance in predicting credit risk. Despite this, it had commendable precision and recall metrics, with an F1-score of 0.83, demonstrating its robustness in identifying creditworthy applicants.

Furthermore, we incorporated K-Fold Cross Validation to ensure a comprehensive and reliable evaluation of the model performance. This approach enabled us to confirm the consistency of our models across different subsets of the data.

As an additional step, we compared the XGBoost model's results with other algorithms, further enriching our report with comparative insights. Surprisingly, the performance of the MLP and KNN algorithms was closely aligned with the Logistic Regression model, which was an unanticipated outcome, emphasizing the value of empirical testing across various algorithms.

In conclusion, our study offered significant insights into the efficacy of different machine learning algorithms for credit risk classification. The top-performing Logistic Regression model with RFE proved to be the most effective in our analysis. These results can guide future research and practical applications, particularly for financial institutions looking to leverage machine learning for credit scoring.

For further information, check out "ProjectReport_Ozge_Serkan.pdf"
