# Framingham Heart Disease Prediction

This repository contains an analysis of the **Framingham Heart Study** dataset to predict the risk of heart disease. The study includes various attributes related to cardiovascular health, and the analysis demonstrates data preprocessing, visualization, and machine learning modeling.

## Dataset Description

The Framingham Heart Study dataset is widely used for predicting heart disease risk based on medical and lifestyle factors. Below is a summary of the key attributes:

| **Attribute**             | **Description**                                                                 |
|---------------------------|---------------------------------------------------------------------------------|
| `Age`                     | Age of the participant (years).                                                |
| `mal`                     | Gender of the participant (0 = Female, 1 = Male).                              |
| `Education`               | Education level attained.                                                      |
| `Current Smoker`          | Current smoker status (1 = Yes, 0 = No).                                       |
| `Cigarettes per Day`      | Number of cigarettes smoked daily.                                             |
| `BP Medication`           | Whether the participant is on blood pressure medication (1 = Yes, 0 = No).     |
| `Prevalent Stroke`        | History of stroke (1 = Yes, 0 = No).                                           |
| `Prevalent Hypertension`  | History of hypertension (1 = Yes, 0 = No).                                     |
| `Diabetes`                | Whether the participant has diabetes (1 = Yes, 0 = No).                        |
| `Cholesterol`             | Total cholesterol level (mg/dL).                                               |
| `Systolic Blood Pressure` | Systolic blood pressure (mm Hg).                                               |
| `Diastolic Blood Pressure`| Diastolic blood pressure (mm Hg).                                              |
| `BMI`                     | Body Mass Index (kg/m²).                                                       |
| `Heart Rate`              | Resting heart rate (beats per minute).                                         |
| `Glucose`                 | Blood glucose level (mg/dL).                                                   |
| `Ten-Year CHD`            | Whether the participant developed heart disease in 10 years (1 = Yes, 0 = No). |

---

## Project Overview

This notebook contains the following steps:

1. **Exploratory Data Analysis (EDA):**
   - Visualization of key attributes to understand data trends and distributions.
   - Identification and treatment of missing or inconsistent data.

2. **Data Preprocessing:**
   - Handling missing values.
   - Feature scaling and encoding.

3. **Model Building:**
   - Application of various machine learning models (e.g., Logistic Regression, Random Forest).
   - Evaluation using metrics such as accuracy, precision, recall, and F1-score.

4. **Insights and Results:**
   - Interpretation of model performance.
   - Key takeaways from the analysis.

---

## Getting Started

### Prerequisites
- Python 3.13
- Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/Framingham-heart-disease.git
```

Install required Python libraries:
```bash
pip install -r requirements.txt
```

Open the notebook:
```bash
jupyter notebook Framingham\ Heart\ disease.ipynb
```

---

## Results

- The model achieved a high accuracy in predicting 10-year heart disease risk.

---

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- The **Framingham Heart Study** dataset is a public dataset available for educational and research purposes.
- Credit to the original notebook [here](https://github.com/v-bhagat/Framingham-heart-Disease/blob/main/Framingham%20Heart%20disease.ipynb) for inspiration.