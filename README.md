# Cancer Diagnosis Multi-Model System 
Presented by :
Omar Helwe (8846) ,
Youssef Jaber (8656)

The system leverages machine learning techniques, such as SVMs, Ensemble Learning, and Explainability methods to ensure model transparency. The project was divided into four key phases (the results for each phase are well highlighted in the notebook provided ):

Exploratory Data Analysis (EDA)

Support Vector Machines (SVMs)

Ensemble Learning

Model Explainability

Phases of the Project
1. Exploratory Data Analysis (EDA)
In the EDA phase, we focused on understanding the dataset, its features, and the distribution of the target variable. Key steps included:

Data Loading: The dataset used in this project is the Breast Cancer Wisconsin dataset (from sklearn).

Data Cleaning and Preprocessing: We checked for missing values and ensured the dataset was ready for machine learning.

Visualizations: We visualized data distributions, correlations between features, and explored any class imbalances or trends.

2. Support Vector Machines (SVMs)
In this phase, we implemented SVM models to classify the cancer dataset. We:

Model Training: Trained the SVM model with different kernel functions (e.g., linear, polynomial and  radial basis function).

Model Evaluation: Evaluated model performance using accuracy, precision, recall, and F1-score.

Hyperparameter Tuning: Fine-tuned the SVM model using grid search to find the best parameters for classification.

3. Ensemble Learning
After implementing SVMs, we applied Ensemble Learning techniques to improve model performance. This phase involved:

Random Forest Classifier: Built a random forest model and fine-tuned it for better accuracy.

Gradient Boosting: We implemented Gradient Boosting Machines (GBM) and evaluated their performance compared to the Random Forest model.

Model Comparison: We compared the results of both ensemble methods (Random Forest and Gradient Boosting) to determine the better model for classifying benign and malignant cancers.

4. Model Explainability
To ensure transparency in our models and gain insights into the decision-making process, we employed Explainability methods:

LIME (Local Interpretable Model-Agnostic Explanations): We used LIME to explain the predictions of our models. This helps understand how different features contribute to the model's classification decision.

SHAP (SHapley Additive exPlanations): We used SHAP to calculate the importance of each feature and visualize their impact on model predictions. This allows us to interpret the model's behavior and ensure it is not making biased decisions.

Visualization: Both LIME and SHAP were used to visualize feature importance and highlight which features were most indicative of malignancy.
