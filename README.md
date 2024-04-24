# Disease Recommendation System

This system is designed to predict diseases based on symptoms provided by the user and recommend precautions accordingly. Additionally, it offers the option to consult doctors specialized in treating the predicted disease.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- numpy
- pandas
- scipy
- matplotlib
- seaborn
- scikit-learn

You can install them using pip:

```
pip install numpy pandas scipy matplotlib seaborn scikit-learn
```

### Input Format

When prompted, input symptoms from the provided list separated by commas. Ensure each symptom is capitalized and there are no spaces between them. For example:

```
Skin Rash,Nodal Skin Eruptions,Joint Pain
```

### Running the Code

1. Clone the repository or download the provided code files.
2. Ensure all necessary CSV files (`training_data.csv`, `test_data.csv`, `symptom_Description.csv`, `symptom_precaution.csv`, `doctors.csv`) are in the same directory as the code files.
3. Run the Python script `disease_recommendation.py`.
4. Follow the prompts to input symptoms and consult a doctor if desired.

## How it Works

1. The system trains multiple classifiers (SVM, Naive Bayes, Random Forest) using training data.
2. User-provided symptoms are used to predict diseases using the trained classifiers.
3. Precautions and descriptions for the predicted disease are displayed.
4. Optionally, users can consult doctors specialized in treating the predicted disease.
