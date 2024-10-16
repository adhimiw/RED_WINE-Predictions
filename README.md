# Red Wine Quality Prediction

## Project Overview
This project aims to predict the quality of red wine using various machine learning models. The analysis was performed using the Orange data mining tool.

## Dataset
The dataset used in this project contains various chemical properties of red wine samples, along with their quality ratings. (You may want to add more details about the dataset here, such as its source and the number of samples.)

## Models Used
We implemented and compared the performance of four different machine learning models:
1. Random Forest (RF)
2. Gradient Boosting (GB)
3. Decision Tree (DT)
4. Support Vector Machine (SVM)

## Methodology
1. Data preprocessing and exploration were performed using Orange.
2. The dataset was split into training and testing sets.
3. Each model was trained on the training data and evaluated on the test data.
4. Model performance was compared using various metrics including accuracy, Area Under the Curve (AUC), and Matthews Correlation Coefficient (MCC).
5. Two sampling techniques were used to validate the results.

## Results
Our analysis yielded the following results:

1. Random Forest:
   - Consistently provided the highest accuracy, AUC, and MCC across both sampling techniques.
   - Proved to be the most reliable model for this dataset.

2. Gradient Boosting:
   - Performed second-best among all models.
   - Showed good performance across all metrics but slightly behind Random Forest in terms of accuracy and robustness.

3. Decision Trees:
   - Offered decent performance but were outclassed by the ensemble methods.
   - May still be useful for their simplicity and interpretability.

4. Support Vector Machine (SVM):
   - Consistently underperformed compared to other models.
   - Deemed unsuitable for this specific dataset and task.

## Conclusions
Based on our comprehensive analysis:

1. Random Forest emerged as the clear winner, demonstrating superior performance in predicting wine quality across different evaluation metrics and sampling techniques.
2. Ensemble methods (Random Forest and Gradient Boosting) significantly outperformed individual models like Decision Trees and SVM.
3. The choice of model can have a substantial impact on prediction accuracy in this domain.

## Final Recommendation
For this wine quality prediction task, we strongly recommend using the Random Forest model. It provides the best generalization across both cross-validation and test scenarios, offering the highest accuracy and robustness among all tested models.

## Future Work
- Explore feature importance to understand which chemical properties have the most significant impact on wine quality.
- Experiment with hyperparameter tuning to potentially improve model performance further.
- Investigate the possibility of creating a simplified model for real-time predictions.

## How to Run
1. Install Orange data mining tool from [https://orangedatamining.com/](https://orangedatamining.com/)
2. Download the project's .ows file
3. Open Orange and load the .ows file
4. (Add any additional steps needed to reproduce your results)

## Contributors
(ADHI_ miw)


For the full license text, please refer to [https://www.gnu.org/licenses/gpl-3.0.en.html](https://www.gnu.org/licenses/gpl-3.0.en.html)
