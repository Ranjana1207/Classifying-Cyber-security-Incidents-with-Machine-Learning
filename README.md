# Classifying-Cyber-security-Incidents-with-Machine-Learning
### Microsoft : Classifying Cybersecurity Incidents with Machine Learning

## Project Overview

The Classifying Cybersecurity Incidents🚨 project is a machine learning-based solution designed to enhance the efficiency of Security Operation Centers (SOCs) at Microsoft. The project focuses on building a classification model that accurately predicts the triage grade of cybersecurity incidents, assisting SOC analysts in prioritizing their efforts and responding to threats efficiently.

## The goal is to classify incidents as:

⁕ True Positive (TP): A confirmed threat.

⁕ Benign Positive (BP): A false alarm.

⁕ False Positive (FP): A misidentified threat.

## Key Features & Skills

This project allows you to dive deep into several crucial aspects of data science and machine learning:

**• Data Preprocessing & Feature Engineering:**

Cleaning and transforming raw data into useful features for model training.

**• Machine Learning Classification Techniques:** 

Employing algorithms like Random Forest, XGBoost, and others for incident classification.

**• Evaluation Metrics:**

Using Macro-F1 Score, Precision, and Recall to assess model performance.

**• Cybersecurity Frameworks:** 

Leveraging the MITRE ATT&CK framework for better understanding of cybersecurity data.

**• Handling Imbalanced Datasets:** 

Implementing strategies like SMOTE, class weights, and ensemble methods to deal with imbalanced data.

**• Model Optimization:** 

Fine-tuning model parameters for optimal performance.

###  Business Use Cases

The developed solution can significantly improve multiple areas of cybersecurity operations:

**Security Operations Centers (SOCs):** 

Automates the triage process and enhances analysts' decision-making.

**Incident Response Automation:** 

Provides SOCs with faster, data-driven insights and recommended actions.

**Threat Intelligence:**

Increases the precision of detecting true and false positives using historical data.

**Enterprise Security Management:** 

Reduces false positives, improves threat detection, and ensures swift incident response.

## Project Approach
**<ins>1. Data Exploration and Preprocessing</ins>**

**(I) Initial Inspection:** 

Load and examine the train dataset (train.csv) to understand the structure, data types, and distribution of the target variable.

**(II) Exploratory Data Analysis (EDA):** 

Visualize patterns, identify correlations, and detect anomalies, particularly class imbalances.

**<ins>2. Model Building</ins>**
 
**(I) Train-Validation Split:** 

Split the data into training and validation sets for effective model evaluation.

**(II) Baseline Model:** 

Start with simple models (e.g., Logistic Regression, Decision Trees) to set a performance benchmark.

**(III) Advanced Models:** 

Use Random Forest, XGBoost, and other sophisticated models for classification.

**(IV) Cross-Validation:** 

Implement k-fold cross-validation to ensure robustness.

**<ins>3. Model Evaluation</ins>**
 
**(I) Performance Metrics:** 

Focus on Macro-F1 Score, Precision, and Recall to measure the model’s ability to generalize to unseen data.

**(II) Hyperparameter Tuning:** 

Use techniques like Grid Search or Random Search to optimize model performance.

**(III) Handling Class Imbalance:** 

Apply methods like SMOTE or adjust class weights to handle class imbalance.

**<ins>4. Final Evaluation</ins>**
 
**(I) Testing:** 

Evaluate the final model using the test dataset (test.csv) and report key metrics.

**(II) Comparison to Baseline:** 

Ensure the model’s performance outperforms the baseline and holds up on unseen data.

## Results:

**📌 Model Performance**: A highly accurate classification model that predicts cybersecurity incident triage grades (TP, BP, FP).

**📌 Feature Analysis**: Insights into which features influence model predictions the most.

**📌 Model Documentation**: Comprehensive process documentation, highlighting each phase from data collection to model evaluation.

## Evaluation Metrics

**🔸 Macro-F1 Score:** Balances precision and recall, providing a holistic view of performance across all classes.

**🔸 Precision:** Measures the proportion of true positive predictions out of all positive predictions.

**🔸 Recall:** Measures the model’s ability to identify all true positives, ensuring critical incidents are not missed.

## Dataset Overview:
               
The GUIDE dataset contains cybersecurity incident records annotated with triage grades (TP, BP, FP). 
               
The data is stratified and includes over 1 million triage-annotated incidents, ensuring a comprehensive representation of real-world security incidents.

### Features:

**🔸 Evidence:** Individual pieces of evidence like IP addresses, emails, and user details.

**🔸 Alerts:** Aggregated evidence signaling a potential security incident.

**🔸 Incidents:** A collection of alerts representing a complete security threat scenario.

### Usage

♦ Load the data from train.csv and test.csv.

♦ Preprocess and engineer features.

♦ Train and evaluate your model.

♦ Check model performance with key metrics (Macro-F1 Score, Precision, Recall).

### Technologies Used

**※ Python:** Main programming language.

**※ Pandas, NumPy:** For data manipulation and processing.

**※ Scikit-Learn:** For building and evaluating machine learning models.

**※ XGBoost, LightGBM:** Advanced boosting algorithms.

**※ Matplotlib, Seaborn:** For data visualization and exploratory analysis.

**※ SMOTE:** Synthetic Minority Over-sampling Technique for class imbalance handling.
