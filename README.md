# Stroke-Prediction
Stroke Prediction Model
Objective:
The goal of this project is to develop a machine learning model to predict the likelihood of a stroke based on clinical features. The dataset used was sourced from Kaggle.

Model:
i used XGBoost (Extreme Gradient Boosting) for this classification task, which performed well with an initial accuracy of 91%. However, the F1 score was suboptimal, particularly due to a high false positive rate.

Improvement:
To address the false positives, hyperparameter tuning was applied using Random Search to find the optimal model settings. This tuning helped reduce false positives while balancing the precision and recall.

Results:
After tuning, the model’s accuracy decreased to 89%, but the F1 score improved significantly, with a notable reduction in false positives. This made the model more reliable for practical use, where minimizing false positives is crucial in healthcare settings.

Conclusion:
While there was a slight drop in overall accuracy, the model is now better balanced, with improved F1 score and reduced false positives, making it more suitable for stroke prediction in real-world applications.
