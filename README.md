# neural-network-challenge-2

Project Overview
This project focused on building a neural network model to predict employee attrition and department assignments. The goal was to leverage machine learning techniques to provide insights into workforce management.

Data Preparation
Data Cleaning: Removed missing values and outliers to ensure data quality.
Encoding: Utilized OneHotEncoder for categorical variables (Attrition and Department) to prepare the data for modeling.
Scaling: Standardized numerical features to improve model performance.
Model Development
Architecture: Designed a neural network with:
An input layer for scaled features.
Two branches for separate outputs (Attrition and Department), each with its own hidden and output layers.
Activation Functions:
Sigmoid for the binary output (Attrition) to provide a probability score.
Softmax for the categorical output (Department) to handle multiple classes effectively.
Training & Evaluation
Training: The model was trained for 100 epochs, achieving high accuracy on both outputs.
Evaluation: Evaluated the model using appropriate metrics, adjusting the focus based on class balance.
Future Improvements
Consider hyperparameter tuning for better performance.
Explore different architectures or additional regularization techniques to reduce overfitting.
Investigate alternative metrics to better assess model effectiveness, especially in imbalanced datasets.
Conclusion
This project was a valuable learning experience in applying neural networks for predictive analytics. I gained insights into data preprocessing, model architecture design, and evaluation strategies, which I look forward to applying in future endeavors.






