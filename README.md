# Confusing-Matrix

## Project Overview
**Confusing-Matrix** is a simple project to demonstrate the use of Logistic Regression to predict lung cancer based on patient data such as age and smoking status. The performance of the model is evaluated using a confusion matrix, along with precision, recall, and F1-score metrics.

## Dataset
The project uses a `large_health_data.csv` dataset containing the following columns:
- `Patient_ID`: Unique identifier for each patient (removed during analysis).
- `Age`: The age of the patient.
- `Smoking_Status`: A categorical column indicating whether the patient is a smoker or non-smoker.
- `Lung_Cancer`: The target column (1 = Positive, 0 = Negative).

## Requirements
- Python 3.8+
- Libraries:
  - `numpy`
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`
    
## Screenshot
![Screenshot (119)](https://github.com/user-attachments/assets/c4a55e8a-82e9-4e1b-8e68-95a45d2347c0)


![Screenshot (120)](https://github.com/user-attachments/assets/369eede4-a803-4d2a-bcc7-5180d5bf8e8c)


You can install the required libraries using the following command:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
