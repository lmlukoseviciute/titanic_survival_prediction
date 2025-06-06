# Titanic Dataset EDA and Survival Prediction

This project uses the classic [Titanic dataset from Kaggle](https://www.kaggle.com/competitions/titanic) to predict passenger survival using a **Random Forest Classifier**. It demonstrates key steps in an end-to-end machine learning workflow, including exploratory data analysis (EDA), data preprocessing, feature engineering, model training, and evaluation.

## Project Workflow

1. **Data Cleaning**
   - Dropped irrelevant features like `Name`, `Ticket`, and `Cabin`
   - Imputed missing values in `Age` (median) and `Embarked` (mode)

2. **Feature Engineering**
   - One-hot encoded categorical variables (`Sex`, `Embarked`)
   - Selected relevant features for modeling

3. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions and survival rates by category
   - Identified important relationships in the data

4. **Modeling**
   - Trained a `RandomForestClassifier` from `scikit-learn`
   - Evaluated performance using accuracy on a held-out test set

5. **Model Performance**
   - Achieved **accuracy of 83.24%** on the test data

---

## Usage

1. **Download the dataset**: You can find the original dataset [on Kaggle](https://www.kaggle.com/competitions/titanic/data).
2. **Install the requirements via**:
   
  ```bash
  pip install -r requirements.txt
  ```
4. **Run the analysis**: Open and execute the `titanic_eda_and_pred.ipynb` notebook to walk through the full analysis.
5. **View Results**: After running the notebook, explore the visual outputs, summary statistics, and significance test results directly in the file.

## Summary

    - Countplots and histograms for EDA
    - Accuracy: 83.24%
    - Decision tree visualization using Graphviz

## License

This project is released under the MIT License.

## Author

Developed by Laima.

Feel free to contribute or suggest improvements!
