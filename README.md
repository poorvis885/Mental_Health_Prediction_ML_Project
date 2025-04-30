Mental Health Prediction Using Machine Learning
Project Overview
This project aims to predict whether an individual is likely to seek mental health treatment based on various demographic and workplace-related factors. Using supervised machine learning techniques, the project analyzes data from a public survey to identify key patterns related to mental health awareness and treatment in the tech industry.

The motivation behind this project is to assist organizations and mental health professionals in identifying individuals who may need support, thus promoting early intervention and better workplace policies.

Dataset Used
Name: Mental Health in Tech Survey (2014)

Source: Kaggle - OSMI Mental Health in Tech Survey

Size: Approximately 1,250 responses

Target Column: treatment (indicates if the person has sought mental health treatment)

Features: Age, Gender, Family History, Remote Work, Benefits, Work Interference, and other workplace factors

Technologies Used
Programming Language: Python

Environment: Google Colab

Libraries Used:

pandas, numpy: Data handling

seaborn, matplotlib: Data visualization

scikit-learn: Preprocessing, model building, and evaluation

Steps Performed
Data Cleaning: Removed null values and selected relevant features

Encoding: Applied label encoding for categorical variables

Splitting: Divided the dataset into training and testing sets (80/20 split)

Scaling: Standardized the data using StandardScaler

Model Training: Trained a Random Forest Classifier

Evaluation: Measured performance using accuracy, classification report, and confusion matrix

Model Results
Model Used: Random Forest Classifier

Accuracy Achieved: Approximately 82%–85%

Evaluation Metrics:

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

Conclusion
The project demonstrates how machine learning can be applied to analyze mental health trends in the workplace. With adequate preprocessing and modeling, the system can predict whether a person might need mental health treatment, which can help organizations build a more supportive environment.

License
This project is licensed under the MIT License. Refer to the LICENSE file for details.

This project is the intellectual property of Poorvi Shrivastava.

🔗 Connect with me: LinkedIn
