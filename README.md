# Mental Health Prediction using Machine Learning

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Model Performance](#model-performance)
- [How to Run](#how-to-run)
- [Results and Conclusion](#results-and-conclusion)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

This project focuses on building a machine learning model to predict whether an individual is likely to seek mental health treatment based on demographic and workplace factors. The goal is to aid organizations and mental health practitioners in identifying individuals who may require support, enabling early intervention.

---

## Dataset

- **Name**: Mental Health in Tech Survey (2014)
- **Source**: [Kaggle - OSMI Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)
- **Size**: ~1,250 records
- **Features**: Includes age, gender, remote work, family history, company size, and more
- **Target Variable**: `treatment` (Yes/No)

---

## Technologies Used

- **Language**: Python 3
- **Environment**: Google Colab
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – ML algorithms, preprocessing, evaluation

---

## Project Workflow

1. **Data Cleaning**: Removed irrelevant columns and handled missing values
2. **Feature Encoding**: Categorical variables encoded using LabelEncoder
3. **Train-Test Split**: 80/20 train-test ratio
4. **Scaling**: Standardized using StandardScaler
5. **Model Training**: Random Forest Classifier used for prediction
6. **Model Evaluation**: Accuracy score, classification report, and confusion matrix

---

## Model Performance

- **Algorithm**: Random Forest Classifier
- **Accuracy Achieved**: ~82–85%
- **Evaluation Metrics**:
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## How to Run

1. Clone the repository or open the Google Colab notebook.
2. Upload the `survey.csv` dataset from Kaggle.
3. Run all the cells in the notebook sequentially.
4. View the model's predictions and performance metrics.

---

## Results and Conclusion

The trained model successfully classifies individuals who are likely to seek mental health treatment. With ~85% accuracy, this model can be a valuable tool for HR departments and mental health professionals to better understand mental health trends within organizations.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- [Kaggle](https://www.kaggle.com) for the dataset  
- [OSMI](https://osmihelp.org/) (Open Sourcing Mental Illness) for the original survey initiative  
- Developed as part of an AICTE internship submission

