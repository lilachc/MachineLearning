# Malware Classification Project

## Project Overview
This project was developed as part of the final project for the Introduction to Machine Learning course at Tel Aviv University's Faculty of Engineering. The primary goal is to build a robust classification model capable of accurately distinguishing between malicious and non-malicious files based on a provided dataset. The project focuses on leveraging various data preprocessing techniques, feature engineering, and machine learning algorithms to achieve high accuracy and reliability in classification.

## Objectives
1. Develop a pipeline to preprocess raw data effectively, including handling missing values, outliers, and encoding categorical features.
2. Engineer and select relevant features to enhance model performance while reducing dimensionality.
3. Experiment with multiple machine learning models to identify the best-performing classifier for this task.
4. Evaluate the models rigorously using appropriate metrics and visualization tools.

## Dataset
The dataset contains labeled records of file attributes, each corresponding to either malicious or non-malicious files. Features include both numerical and categorical data, requiring preprocessing and transformations to optimize for machine learning algorithms.

### Key Dataset Characteristics:
- **Features**: Various file attributes, such as size, strings count, and headers.
- **Target**: Binary classification labels (“Malicious” and “Non-Malicious”).
- **Challenges**: Imbalanced classes, high-dimensional data, and potential noise.

## Methodology
1. **Data Preprocessing**
   - Handled missing values using statistical imputation.
   - Detected and treated outliers using techniques like IQR and percentile capping.
   - Encoded categorical features using ordinal encoding based on frequency.

2. **Feature Engineering**
   - Performed correlation analysis to remove highly correlated features.
   - Applied dimensionality reduction methods such as Principal Component Analysis (PCA).

3. **Model Development**
   - Experimented with various machine learning models, including Logistic Regression, Random Forest, XGBoost, and Multi-Layer Perceptron (MLP).
   - Tuned hyperparameters using grid search for optimal performance.

4. **Evaluation**
   - Used metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
   - Visualized results using confusion matrices and ROC curves.

## Results
The project achieved high classification accuracy and strong evaluation metrics across various models. Notably, the Random Forest and XGBoost classifiers delivered the best results, with a strong balance of precision and recall.

## Key Findings
- Feature engineering significantly improved model performance, particularly through dimensionality reduction.
- Handling imbalanced data via proper evaluation metrics and resampling methods ensured reliable predictions.
- Hyperparameter tuning and model selection were critical to optimizing performance.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, XGBoost
- **Environment**: Jupyter Notebook

## Conclusion
This project demonstrated a comprehensive approach to solving a classification problem in the context of cybersecurity. By employing robust preprocessing, feature engineering, and model evaluation, the final solution offers a reliable tool for detecting malicious files. Future work could involve expanding the dataset, testing additional algorithms, and deploying the model in a real-world application.

## Authors
- Lilach Cohen
- Noa Levy

