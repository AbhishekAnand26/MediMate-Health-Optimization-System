# Personalised-Medical-Recommendation-System 

# Problem Statement
The healthcare industry is continually seeking innovative solutions to provide more accurate and accessible medical diagnostics. The AI Doctor project aims to build an intelligent system that can assist doctors by predicting potential diseases or health conditions based on patients' symptoms and medical data. This automated system helps streamline diagnostics, providing faster and more data-driven healthcare recommendations.

# Objective
The goal of this project is to develop a machine learning model capable of predicting medical conditions based on symptoms and patient data. This system can aid medical professionals by offering preliminary diagnoses, improving healthcare delivery, and supporting patient care.

# Project Workflow
1. Data Collection
   
   The dataset includes patient data such as symptoms, medical history, age, gender, and other clinical details. This dataset serves as the foundation for training the model to predict possible 
   health conditions.

2. Data Analysis and Preprocessing

    Exploratory Data Analysis (EDA): The collected data is analyzed to identify patterns and relationships between symptoms and diseases. Data visualization techniques are used to gain insights.
 
    Preprocessing: Includes handling missing values, encoding categorical variables (such as symptoms), and normalizing numerical data. This step ensures the dataset is clean and ready for model 
    training.

3. Model Selection
   
   The project uses classification algorithms to predict possible diseases based on symptoms. Models such as Random Forest, Decision Trees, and K-Nearest Neighbors (KNN) are trained and evaluated 
   for accuracy.

    Random Forest : Captures complex relationships between features and is robust to overfitting.
   
    Decision Trees : Provides clear, interpretable decision paths.
   
    KNN : Helps classify based on the proximity of symptoms to known disease cases.
  
4. Train-Test Split
   
   The dataset is divided into training and testing sets. The training data is used to teach the model how symptoms relate to specific diseases, while the test data is used to evaluate how well the 
   model generalizes to new, unseen data.

5. Model Training and Evaluation
   
   The models are trained using various algorithms, and their performance is evaluated using metrics such as:

   Accuracy : Measures the percentage of correct predictions.
   
   Precision, Recall, F1-Score : Evaluates the balance between correctly identifying diseases and avoiding false positives.
   
   Confusion Matrix : Visualizes the performance across different disease classes.

6. Prediction on New Patient Data
   
   Once the models are trained, they can be used to predict potential diseases for new patients based on their input symptoms. This functionality can serve as a decision-support tool for doctors, 
   providing real-time insights into patient diagnoses.

# Conclusion
The AI Doctor project demonstrates the power of machine learning in healthcare. By leveraging patient data and symptom analysis, the system provides an intelligent method for disease prediction, supporting medical professionals in diagnostics. Further enhancements could include more advanced models, larger datasets, and integration with real-world patient data to improve accuracy.
