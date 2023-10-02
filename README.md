# Low Birth Weight Prediction Project

This repository contains Python code and resources for predicting low birth weight in newborn babies based on parental data. The project utilizes various features such as parents' age, race, education, and habits like smoking and drinking to make predictions regarding whether the newborn will be underweight or not.

## Overview

Low birth weight in newborns is a critical health concern, and this project aims to create a predictive model to help identify babies at risk. By analyzing data related to the parents, we can provide valuable insights and early warning indicators to healthcare professionals.

## Dataset

The dataset used in this project is included with the code files in the repository. It consists of 196 tuples and 18 features. The most important features include:

- `mage`: Mother's age
- `meduc`: Mother's education
- `monpre`: Mother's prenatal condition
- `npvis`: Number of visits to the clinic
- `fage`: Father's age
- `feduc`: Father's education
- `omaps`, `maps`, `cigs`: Smoking-related features
- `drinks`: Drinking habit
- `male`: Gender of the newborn
- `(mwhite, mblack, moth, fwhite, fblack, foth)`: Race of parents
- `bwght`: Birth weight

## Getting Started

Follow these steps to get started with the project:

### Prerequisites

Before running the code, ensure you have the required Python libraries installed. You can install them using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Code

Clone this repository to your local machine:

```bash
git clone https://github.com/AdityaJak/Low_Birth_Weight_Prediction.git
```

Navigate to the project directory:

```bash
cd Low_birth_weight_Prediction
```

### Usage

1. Open the Jupyter Notebook file `birthweight_low.ipynb`.

2. Execute the code cells in the notebook to perform the following tasks:
   - Data loading and preprocessing.
   - Exploratory data analysis (EDA) to understand the dataset.
   - Feature selection and engineering.
   - Building and training predictive models.
   - Model evaluation and performance metrics.

3. Customize the notebook to fit your specific requirements or experiment with different machine learning algorithms.

## Results and Evaluation

The project evaluates the predictive models using various metrics such as accuracy, precision, recall, and F1-score to determine their effectiveness in predicting low birth weight.

## Acknowledgments

- This project is for educational purposes and should not be used as a sole basis for medical decisions.
- Always consult with healthcare professionals for accurate medical assessments.

## Author

[Adithya Jakkaraju]

Feel free to reach out with any questions or suggestions!

We hope this project contributes to the early identification of low birth weight risks and improves newborn care. Thank you for your interest and support!
